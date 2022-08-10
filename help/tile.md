---
layout: help
title: tile
syntax:
  - tile
  - tilematch
  - tilematch next
---

These commands only work within your home plane.  Type 'tile' to view the data 
of the tile you're currently standing on.  A tile consists of 10 by 10 plots, 
each of which is a terrain type.  For example tile 2 consists of 10 by 10 plots
of plain, while tile 103 is the same except for having a river flowing through 
it (thus including plots for riverbank and east-flowing river).  You will also 
see whether or not the current tile matches the surrounding tiles.

The 'tilematch' command checks your entire home plane for non-matching tiles, 
starting with the bottom left corner and finishing with the top right corner.  
The search will be stopped if a non-matching tile is found, and you will be 
transported to that location.  If you type 'tilematch next', you will move on 
to the next non-matching tile.

See also: terraform home zone
