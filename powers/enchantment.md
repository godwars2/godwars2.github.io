---
layout: power
title: Enchantment
description: You are able to enchant and unenchant items.
info:
  Required class      : Mage
  Power sphere        : Crafting
reqs:
  Requirements        : None
---

This power allows you to magically adjust equipment, stripping away existing
bonuses and adding new ones.  You may add bonuses to an item with the 'enchant'
command, with each bonus increasing the Enchantment value of the item by the
specified amount.  You can also use the 'unenchant' command to remove bonuses
from an item, as long as you have not already added Enchantment points to it
(in other words, once you enchant an item, you immediately lose the option to
ever again unenchant it).  Each removed bonus increases the Unenchantment value
and reduces the radiation of the item by the specified amount, although the
Unenchantment value can never exceed the remaining radiation.

Note that unenchant also has a reroll option.  This increases the Unenchantment
value of the item by 50, and randomly rerolls its bonuses (see 'help items').

The most Enchantment and Unenchantment you can place in a single item is 50 per
rank.  Equally, you can wear 50 points of each of Enchantment and Unenchantment
per rank, divided among any number of worn items, without penalty.  Each point
beyond that will be treated as if it were a point of radiation.
