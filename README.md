sublime_ino
===========

A build system plugin for [Sublime Text](http://www.sublimetext.com/) which calls the ~~ino tool~~ [ano / arturo tool](https://github.com/scottdarch/Arturo) for either:

-Compile: [CTRL]+B

-Clean: [CTRL]+[ALT]+B
-(Compile and) Upload: [CTRL]+[SHIFT]+B  (aka. run)

Put the both files into your `~/.config/sublime-text-3/Packages/User/` directory.

The clean and upload commands require modification of your user key bindings, which is why it is included here. Be careful to merge if the file already exists, to keep existing settings!

Activate the build system by choosing: `Tools -> Build System -> sublime_ino`

if you want auto, you need to fidget with an arduino language definition.. I'll teach you later. (hint: "selector": "source.c++.arduino" )

happy hacking :)
~Robotto
