Sublime Line Endings Unify
===============================

change files endings (`Mac`,`Unix`,`Windows`) to `Unix` (aka `\n`).  (windows with sublime3 will be `Windows` (aka `\r\n`))


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `LineEndingsUnify` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## How to use:

 - drag folder to sublime
 - use `cmd+shift+P` then `Line Endings Unify`
 - or bind some key in your user key binding:
  ```js
    {
	 "keys": ["ctrl+alt+shift+l"],
	 "command": "line_endings_unify"
	}
  ```
 - check file extentions to be handled
 - done

**always backup your data**

 [0]: http://wbond.net/sublime_packages/package_control
