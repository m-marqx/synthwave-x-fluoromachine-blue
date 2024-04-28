# synthwave-x-fluoromachine
This is a fork of @webrender's synthwave-x-fluoromachine, which is also fork of @robbowen's Synthwave '84 theme, merged with @fullerenedream's Fluoromachine theme for VSCode, with @thecodemonkey synthwave-x-fluoromachine-epic-animations extras.

# Installation (github)
1. Install this theme
2. install Custom CSS and JS Loader
3. link the CSS file from this extension in your vscode settings.json:

On Mac it might look something like the snippet below:

```{
  "vscode_custom_css.imports": [
    "file:///Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-blue.css""
    "file:///Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-extras.css""
    ]
}
```

Windows might resemble:

```{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-blue.css",
    "file:///C:/Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-extras.css"
    ]
}
```
4. `synthwave-x-fluoromachine-extras.css` is optional.
5. From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.
