---
layout: help
title: armour
syntax:
  - armour
  - armour <worn/total/spell/natural/immunity/bypass>
  - armour <cut/stab/etc> <face/body/etc> <damage> (<bypass>)
---

This command lists the total percentage damage soaked by a blow after it has 
passed through all of your layers of armour (including natural and immunity), 
for each body location, vs each type of damage.  The second value (after the %)
is the auto-absorb - eg '50%/5' means 50% soak and 5 points of auto-absorb.

Each layer of armour you wear soaks a percentage of the damage that strikes it.
For example, if wearing a breastplate and a chainmail shirt, and both soaked 
50% damage, when struck by 100 points of damage the breastplate would soak the 
first 50 and the chainmail shirt the next 25 (i.e., 50% of the 50 damage that 
got past the breastplate).  No single layer of armour can soak more than 75% 
damage, and will be capped at 75% after applying bypass (see 'help bypass').

After worn armour comes your spell armour, then your natural armour, each of 
which are treated exactly like a layer of worn armour.

If your total bypass is 3% or more of your opponent's total armour, then at 
least 1% of your total damage is guaranteed to get through their combined 
armour layers.  This increases to 2% if your bypass is 6% of their armour, 3% 
at 9%, 4% at 12%, 5% at 15%, and so on, up to a maximum of 33% damage at 99%.

If your opponent's total armour is 3% or more of your total bypass, then at
least 1% of your total damage will be soaked by their combined armour layers.  
This increases to 2% damage if their armour is 6% of your bypass, 3% at 9%, 4% 
at 12%, 5% at 15%, and so on, up to a maximum of 33% damage at 99%.

Last but not least comes your immunity, which is treated the same as natural 
armour except that it is capped at 95%, and cannot be bypassed.

After applying all soak percentages, your total auto-absorb is subtracted from
the remaining damage.  This auto-absorb will typically be the same as the
total of all encumbrance worn on the struck location, although it may well be
adjusted by talents, powers and magical item bonuses.  If struck by a critical
hit, your opponent's total bypass will be subtracted from your auto-absorb.
