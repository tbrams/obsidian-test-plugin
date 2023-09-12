# Modified Obsidian Sample Plugin

This is a slightly modified version of the sample plugin provided by Obsidian (https://obsidian.md).

This project uses Typescript to provide type checking and documentation.
The repo depends on the latest plugin API (obsidian.d.ts) in Typescript Definition format, which contains TSDoc comments describing what it does.

**Note:** The Obsidian API is still in early alpha and is subject to change at any time!

This sample plugin demonstrates some of the basic functionality the plugin API can do.
- Adds a ribbon icon, which shows a Notice when clicked.
- Adds a command "Open Sample Modal" which opens a Modal.
- Adds a plugin setting tab to the settings page.
- Registers a global click event and output 'click' to the console.
- Registers a global interval which logs 'setInterval' to the console.

Additional features:
- Using a bird icon instead of dices 
- Logging in the console when plugin is loaded
- Added a status bar with fruit emojis in the lower part of the app window
- Added markdown post processor (csv data -> html table)
- Console log of any new file created in the vault
- Added a command "Sample Plugin: Print greeting to console
- Added a command the will type the selected text in the console
- Console log when unloading the plugin