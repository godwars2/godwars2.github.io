---
layout: help
title: colour
syntax:
  - colour <on/off/ansi/xterm>
  - colour <good/okay/bad/awful> <colour/COLOUR>
  - colour <say/chat/tell/gossip/newbie/pray> <colour/COLOUR>
  - colour <name/backstab> <colour/COLOUR>
  - colour <info/war> <colour/COLOUR>
  - colour <YouSweepThem/YouHitThem/YouCritThem> <colour/COLOUR>
  - colour <TheySweepYou/TheyHitYou/TheyCritYou> <colour/COLOUR>
---

This command allows you to switch colour on/off, as well as customise your 
scaled colours (which are used for things like health, encumbrance, pain, etc)
and various other default colours.  Note that if you enter the colour name in 
uppercase (eg 'colour good CYAN') it will use bright colours, while 
entering it in lowercase (eg 'colour good cyan') will use dull colours.

Your colours are currently set to CYAN/BLUE/MAGENTA/RED.

Available colours are GREY/RED/GREEN/YELLOW/BLUE/MAGENTA/CYAN/WHITE, as well as
their lowercase equivalents.  As your client supports 256 colours, you may also
specify a three digit 'rgb' sequence, with each digit representing a colour 
intensity from 0 to 5 (eg '533' for pink, '530 for orange, etc).  If you wish 
to include a background colour as well, just add three more digits to the end.

You may also use colour codes within your prompt, or for the display command, 
as follows: ^R (light red), ^r (dark red), ^G (light green), ^g (dark green), 
^Y (light yellow), ^y (dark yellow), ^B (light blue), ^b (dark blue), ^M (light
magenta), ^m (dark magenta), ^C (light cyan), ^c (dark cyan) and ^W (white).

Your client supports extended colours, so you may also use: ^A (light azure), 
^a (dark azure), ^J (light jade), ^j (dark jade), ^L (light lime), ^l (dark 
lime), ^P (light pink), ^p (dark pink), ^V (light violet), ^v (dark violet), 
^T (light tan), ^t (dark tan), ^O (light orange) and ^o (dark orange).

There's also: ^1 (good), ^2 (okay), ^3 (bad), ^4 (awful), ^5 (chat), ^6 (say).
