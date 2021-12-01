---
layout: help
title: hotkey
syntax:
  - hotkey <1-12> <name> <action>
---

This command sets the hotkeys (F1 to F12) if you're using the MSDP plugin.  You
may then either hit the function key or press the button with your mouse to 
trigger the specified action.

The name you specify will be used as a label for the button.  It cannot exceed
12 characters, and cannot contain spaces.

For example, typing 'hotkey 1 What? what' would add the label 'What?' to the 
F1 button on the plugin, and hitting F1 or pressing the button would send the 
'what' command to the server.

Note that the F1 key may also bring up a help window.  To get rid of this, go 
to File -> Global Preferences -> General and toggle "F1, F6 are macros".

See also: msdp
