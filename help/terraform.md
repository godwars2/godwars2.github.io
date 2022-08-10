---
layout: help
title: terraform
syntax:
  - terraform <ocean/lake/plain/forest/mountain/desert/marsh>
  - terraform next
---

This command only works within your home plane.  Type 'terraform plain' to 
change the ocean in your current tile to solid plain, and the surrounding 8 
tiles will be converted to coast.  Type 'area' to see your entire plane, and 
use 'nn', 'ss', 'ee' and 'ww' commands to move one or more tiles at a time.

Only a plain can go right up to the ocean, so in order to create forests, 
mountains, etc, you'll need to make a larger plain first and then place the 
new terrain type in the centre of that.

You may also type 'terraform next', which will cycle to the next tile that 
fits your current location without changing any of the surrounding tiles (for
example you might have a pond or a clearing in your forest).  To view the 
metadata for your current tile, type 'tile'.

See also: home tile zone
