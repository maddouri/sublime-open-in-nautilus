# Open in Nemo

## Overview

This is a simple Sublime Text 3 package that adds a hotkey and a command to reveal a file in its parent directory with the Nemo file manager.

## Usage

The hotkey defaults to <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd>. Use the `open_folder_in_nemo` command in your key bindings to customize it, e.g.:


```json
[
    {
      "keys": ["alt+shift+f"], "command": "open_folder_in_nemo"
    }
]
```

In addition to the hotkey, you can access the plugin via the command palette (command: *Open in Nemo file manager*).

## License

This plugin is licensed under the [GNU GPLv3](http://www.gnu.de/documents/gpl-3.0.en.html). A copy of the license is included in the LICENSE file that accompanies this README.

*Copyright 2014 Glutanimate*: original plugin, https://github.com/glutanimate/sublime-open-in-nautilus)

*Copyright 2017 Yassine MADDOURI*
