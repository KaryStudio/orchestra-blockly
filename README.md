# Orchestra Blockly
This is the fork we made of Blockly to make it suitable for [Orchestra](http://www.karyfoundation.org/research/orchestra). It includes our special needs:
- Fully Offline: So that we can use it on Electron
- Custom Design: To suit our design harmony
- Custom Core Functions: Like for example the way block help works


## Changes made to the base
- In Block SVG (from Core), the definition of `Blockly.BlockSvg.prototype.showHelp_` was changed (Check [this issue](https://github.com/google/blockly/issues/641) for more details)
- Updating `https://blockly-demo.appspot.com/static/media/` path to `./blockly-core/media/` in all files to make the sounds available offline

<br />
<a href="http://www.karyfoundation.org/">
    <img src="http://www.karyfoundation.org/foundation/logo/github-full-horse.png" width="250"/>
</a>