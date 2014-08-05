sublime_ino
===========

A build system plugin for [Sublime Text](http://www.sublimetext.com/) which calls the [ino tool](http://inotool.org/) for either:

-Compile: [CTRL]+B   
-Clean: [CTRL]+[ALT]+B   
-(Compile and) Upload: [CTRL]+[SHIFT]+B   

Put the sublime.build file into your `~/.config/sublime-text-3/Packages/User/` directory.

The _optional_ clean command requires modification of your user key bindings: `Preferences -> Key Bindings - User`

mine looks like this:
```xml
[{ "keys": ["ctrl+alt+b"], "command": "build", "args": {"variant": "Clean"} }]
```

The standard keymap already includes the shortcuts for 'build' and 'run' (upload) so these work out of the box.

happy hacking :)
~Robotto
