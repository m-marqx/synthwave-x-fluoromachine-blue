# synthwave-x-fluoromachine
This is a fork of @webrender's synthwave-x-fluoromachine, which is also fork of @robbowen's Synthwave '84 theme, merged with @fullerenedream's Fluoromachine theme for VSCode, with @thecodemonkey synthwave-x-fluoromachine-epic-animations extras.

# Installation (github)
- Click here or Download Zip of the code on Code button
- Extract all Files on VS Code extension folder
- install Custom CSS and JS Loader
- link the CSS file from this extension in your vscode settings.json:

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
    "file:///C:/Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-np-dark-blue.css",
    "file:///C:/Users/{user name}/.vscode/extensions/Synthwave-x-fluoromachine-blue/synthwave-x-fluoromachine-extras-dark-blue.css"
    ]
}
```

- From the command panel, select Reload Custom CSS and JS. You'll need to run this command every time vscode updates.
