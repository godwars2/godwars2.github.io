---
layout: help
title: resistance
---

Resistance represents your character's physical toughness and ability to shrug 
off damage, and is calculated as follows:

1) Add together all the stat modifiers (Mettle, Size and Discipline).
2) Add bonuses from magical items, and most talents and powers.
3) Apply fighting style percentage modifier.
4) Add bonuses from talents/powers that specifically state 'after percentages'.
5) Add bonuses from spell affects.

When someone strikes you in combat, their Core Damage is calculated (in exactly
the same way as your Resistance), multiplied by 100, then divided by the sum of
their Core Damage and your Resistance, rounded up.  This is then applied as a 
percentage to their actual Damage rating (so if their Core Damage is exactly 
the same as your Resistance, their maximum damage will be half of their Damage,
as described in 'help damage').  This percentage will never fall below 25%.

Once the damage has been calculated, your armour will soak a percentage, then 
auto-absorb is applied, and then any remaining damage is subtracted from your 
health (see 'help health').

See also: assist attack combat damage defence
