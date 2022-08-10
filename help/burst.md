---
layout: help
title: burst
---

Certain attacks have a chance of inflicting a burst, usually only on a critical
hit (see 'help critical').  A burst is treated as an exact duplicate of the 
fighting technique that caused it, except that it usually inflicts a different 
damage type, sometimes hits a different body part, occurs instantly and never 
misses (although a roll to hit is still made to determine the effectiveness of 
the burst attack).  This means that the burst has the same attack (and attack 
strength), damage, natural bypass, etc, as the technique that caused it.

You cannot inflict more than one burst per attack.  If you have a percentage 
chance of causing multiple bursts of different damage types, then the mud will 
go through them in the following order: Storm Talons, poison, fire, lightning, 
sonic, frost.  If a burst fails its percentage chance to perform, then the next
will be checked, until a burst is performed or there are no more left to try.

Bursts of the same damage type from multiple sources do not stack.  For example
a vampire with Umbrage hand runes (gives a percentage chance of causing a cold 
burst) who has House DarkBlade and wields a darkblade (also gives a percentage 
chance of causing a cold burst) will only get the percentage burst chance from 
the darkblade, not from the runes, because both have the same damage type.  If 
the vampire instead had the Ember rune (fire burst) then the mud would check 
for the fire burst first (fire has a higher priority than frost), and if that 
percentage failed, then check for the frost burst from the darkblade.
