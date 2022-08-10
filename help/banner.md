---
layout: help
title: banner
syntax:
  - banner
  - banner line <1-32> <letter/s>
  - banner column <1-64> <letter/s>
  - banner <1-32> <1-64> <letter>
  - banner replace <old letter> <new letter>
  - banner copy <from line> <to line>
---

This command allows you to design a banner for your pantheon.  The banner must 
be 64 characters wide and 32 characters high, and consist solely of letters.

The letters will be converted into coloured pixels: B/G/R/Y/M/C for light blue,
green, red, yellow, magenta and cyan, lower case letters for dark colours.  You
may also use A/J/L/P/V/T/O for the extended colours azure, jade, lime, pink, 
violet, tan and orange.  'W' is bright white, while 'w' is more of a grey, and 
any other letter is black.

For example, to make line 10 all light blue, type 'banner line 10 B', to make 
column 1 orange, type 'banner column 1 RY' (it will alternate red and yellow, 
which will appear orange on the banner).  To turn the top left character dark 
red type 'banner 1 1 r'.

This command only works on your home plane, and is available to the Supreme and
Major Gods.  The banner will be shown on the MWI (http://www.godwars2.org/mwi).
