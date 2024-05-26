# synthwave-x-fluoromachine
This is a fork of @robbowen's [Synthwave '84 theme](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode), merged with @fullerenedream's [Fluoromachine](https://colorsublime.github.io/themes/FluoroMachine/) theme for VSCode.

Furthermore, this is a fork of the [original fork](https://github.com/webrender/synthwave-x-fluoromachine), which removes the background perspective lines, makes the horizontal background lines darker, and makes the menu item selection color brighter.

**The screenshsot below is of the original theme; it does not show the changes that I have made.**

![Theme screenshot](https://repository-images.githubusercontent.com/184457193/69dcff00-14d2-11ea-90e1-4bdf6fef80ca)

## Installation 

• install this theme  
• install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)  
• link the CSS file from this extension in your vscode settings.json: 


```
On Mac it might look something like the snippet below:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.14/synthwave-x-fluoromachine.css"
    ]
}

Windows might resemble:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.14/synthwave-x-fluoromachine.css"
    ]
}
```
• From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.

## Font
The font being used in the screenshot above is [Operator Mono with Ligatures](https://github.com/kiliman/operator-mono-lig).
