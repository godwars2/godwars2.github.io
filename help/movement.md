---
layout: help
title: movement
syntax:
  - n/s/e/w/u/d
  - n/s/e/w/u/d <distance>
  - n/s/e/w/u/d <distance> yards/chains/furlongs/miles/leagues/tiles
---

These commands allow you to move around, by setting your destination to the 
specified offset of your currently selected destination (which by default is 
your current location).  If you don't specify a distance, then you will move a 
default distance based on the scale of the area you are in.

For example, if you are standing at coordinate position 0/0 and type 'n 20', 
your destination will be set to 20/0 and you will immediately start moving 
(unless you are intentionally standing still) towards that location.  Should 
you then type 'e 10', the destination will become '20/10' and you will start 
moving east as well as north.

This command will override any current 'target' (and vice versa).  Select your 
movement speed by typing 'ff' (feet forwards) and 'fb' (feet backwards).

Note that you may also use 'ne', 'nw', 'se' and 'sw' to move diagonally.  These
commands are the same as typing both directions separately - so 'ne 100' would 
set your destination to 100 north and 100 east (i.e., 141 feet north-east).

See also: clear rate target
