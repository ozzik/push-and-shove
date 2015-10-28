# Push and Shove
A tiny Sketch plugin for manipulating layers in various evil ways:

- Resize layers backwards (from the bottom right edge) by just adding ```^``` to your combo: ```^ ⌘ →``` (ctrl + cmd + any arrow key) and ```^ ⌘ ⇧ →``` for 10px (ctrl + cmd shift + any arrow key)
- Move layers half a pixel in any direction with ```^ ⎇ →``` (ctrl + alt + any arrow key)
- Resize layers half a pixel in any direction with ```^ ⎇ ⌘ →``` (ctrl + alt + cmd + any arrow key)
- Toggle the proportions constraint of a layer(s) with ```^ ⌘ c``` (ctrl + cmd + C).

## How to Install
1. Download and open ```push-and-shove-master.zip```
2. Open ```push-and-shove.sketchplugin``` (Sketch will automatically install the plugin)

## Notes
* Tested on Sketch 3.4
* Toggle proportions constraint works with any layers except for text and slices
* For some reason, Sketch's inspector pane doesn't show the updated state (new x/y, width and so on) unless you unselect the layer and reselect it... it's still working :)