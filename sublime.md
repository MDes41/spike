#Sublime




###Download Sublime Text

Navagate to the sublime text website


http://www.sublimetext.com/


download sublime text 3 move it to application and open the once.


###Next install Package controll

The simplest method of installation is through the Sublime Text console. The console is accessed via the ctrl+` shortcut or the View > Show Console menu. Once open, paste the appropriate Python code for your version of Sublime Text into the console.


https://packagecontrol.io/installation

copy and paste the script for sublime 3 into you console click enter.


###Start installing packages

to open package control ` cmd+shift+P ` type install packages click enter.  Type the package you want.  Look them up first at

https://packagecontrol.io/browse/popular

* SublimeERB

 ###Manual Installation

	Clone the repository and symlink file to Sublime's User Directory:

	###OS X

 	``` 
 	git clone git@github.com:eddorre/SublimeERB.git ~/.sublime_erb

	ln -fs ~/.sublime_erb/ ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/SublimeERB
	```

	###Add Keybinding

Open your User Keybinding File and add the following keybinding to activate the toggle command in all file types:

```
  [
    { "keys": ["ctrl+shift+."], "command": "erb" }
  ]
  ```

...or only in the most common ERB contexts:

```
  [
    { "keys": ["ctrl+shift+."], "command": "erb", "context":
      [
        { "key": "selector", "operator": "equal", "operand": "text.html.ruby, text.haml, source.yaml, source.css, source.scss, source.js, source.coffee" }
      ]
    }
  ]
  ```

Now you can use ctrl+shift+. to create and toggle between ERB tags. NOTE: On a Mac use the command key for the ctrl key.

###Some that I like

 * SideBarEnhancements
 * ColorHighlighter
 * Markdown Preview


