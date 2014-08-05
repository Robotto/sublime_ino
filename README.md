sublime_ino
===========

A build system plugin for Sublime Text which calls the ino tool for either compile ( [CTRL]+b ), clean ( [CTRL]+[ALT]+b ) or, (compile and) upload ( [CTRL]+[SHIFT]+b )

clean command requires modification of your user keymap (~/.config/sublime-text-3/Packages/User/Default.sublime-keymap):


[
    { "keys": ["ctrl+alt+b"], "command": "build", "args": {"variant": "Clean"} }
]

the standard keymap already includes the shortcuts for 'buid' and 'run'
