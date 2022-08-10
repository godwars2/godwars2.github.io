---
layout: help
title: zone
syntax:
  - zone
  - zone <sea/land> (-t/-b/-l/-r/-tl/-tr/-bl/-br) (0-10)
---

This command only works within your home plane.  Type 'zone' to view the 
tile IDs for your entire home plane.  If you add arguments to the command, it 
will replace your entire plane with the specified default zone.

For example, typing 'zone land-t' will change your home plane so that the 
top half is land and the rest is sea, while 'zone sea-br' will change it 
so that the bottom-right is sea and the rest is land.  Some zones have a 
selection of different types, and you may alternate between these by 
specifying the ID - for example 'zone land 1', 'zone land 2', etc.

See also: home terraform
