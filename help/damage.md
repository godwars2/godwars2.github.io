---
layout: help
title: damage
---

Damage represents the raw physical power of your character, and is calculated 
in six steps for each body location as follows:

1. Add together the stat modifiers and subtract any weapon penalties.
2. Add any modifiers for the weapon table and bonuses for the weapon itself.
3. Add any modifiers for magical items you're wearing.
4. Apply the percentage modifier if using a two-handed weapon.
5. Add bonuses from talents/powers that specifically state 'after percentages'.
6. Add any modifiers for spell affects.

The maximum damage you can inflict is then calculated by multiplying your 
Damage by a percentage value based on the difference between your Core Damage 
and your opponent's Resistance (see 'help resistance').  Note that percentage 
modifiers for fighting styles are ONLY applied to Core Damage.

The actual amount of damage you inflict will depend upon how well you hit your 
opponent, weighed increasingly in your favour the higher above 50% your chance 
to hit is.  With a 50% chance to hit you'll do an average of 25.7% damage per 
blow (treating misses as 0% damage).  This goes up to 31.82% at 55%, 38.75% at 
60%, 45.38% at 65%, 51.79% at 70%, 58.00% at 75%, 64.06% at 80%, 70.00% at 85%,
75.83% at 90% and 81.58% damage at 95% chance to hit.

In your score, your damage for each location is colour-coded to indicate its
bypass bonus:

Default colour | Defence needed to counter the attack
--- | ---
cyan | 20% of your weapon skill
blue | 10% of your weapon skill
purple | 5% of your weapon skill
red | no bypass bonus

See also: assist attack combat critical defence resistance
