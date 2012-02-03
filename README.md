# dat.GUI

A lightweight graphical user interface for changing variables in JavaScript.

Get started with dat.GUI by reading the tutorial at [http://workshop.chromeexperiments.com/examples/gui](http://workshop.chromeexperiments.com/examples/gui).

## Change log

### 0.5

* Moved to requirejs for dependency management.
* Changed global namespace from *DAT* to *dat* (lowercase).
* Added support for color controllers. See [Color Controllers](http://workshop.chromeexperiments.com/examples/gui/#4--Color-Controllers).
* Added support for folders. See [Folders](http://workshop.chromeexperiments.com/examples/gui/#3--Folders).
* Added support for saving named presets.  See [Presets](http://workshop.chromeexperiments.com/examples/gui/examples/gui/#6--Presets).
* Removed `height` parameter from GUI constructor. Scrollbar automatically induced when window is too short.
* `dat.GUI.autoPlace` parameter removed. Use `new dat.GUI( { autoPlace: false } )`. See [Custom Placement](http://workshop.chromeexperiments.com/examples/gui/#9--Custom-Placement).
* `gui.autoListen` and `gui.listenAll()` removed. See [Updating The Display Manually](http://workshop.chromeexperiments.com/examples/gui/#11--Updating-the-Display-Manually).
* `dat.GUI.load` removed. See [Saving Values](http://workshop.chromeexperiments.com/examples/gui/#5--Saving-Values).
* Made Controller code completely agnostic of GUI. Controllers can easily be created independent of a GUI panel.

## Thanks

The following libraries / open-source projects were used in the development of dat.GUI:

* [require.js](http://requirejs.org/)
* [Sass](http://sass-lang.com/)
* [node.js](http://nodejs.org/)
* [QUnit](https://github.com/jquery/qunit) / [jquery](http://jquery.com/)
