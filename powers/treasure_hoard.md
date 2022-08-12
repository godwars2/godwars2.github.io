---
layout: power
title: Treasure Hoard
description: You can draw power from your treasure hoard.
info:
  Required class      : Dragon
  Power sphere        : Buff
reqs:
  Required powers     : Dragon Form 5+
  Banned powers       : Dragon Barding and Summon Rider
---

Most dragons are notoriously greedy, and will gather a large hoard of treasure
which they jealously guard.  This power allows you to drain the magical energy
from your treasure hoard, and use it to infuse yourself with various bonuses.

Use the 'hoard' command to configure the bonuses and add items to the hoard as
fuel.  The item vanishes and you gain an amount of fuel equal to the age of the
monster it came from (times 10 for uncommon and times 100 for rare items).  If
the item is uncommon or rare, you unlock a +1 or +2 bypass bonus, which can be
added like any other bonus.  The first legendary, mythical, relic and artifact
item of each material you add will permanently increase the scale bonus by +1.

The bonuses from your hoard last 60 seconds, +15 seconds per rank.  Only those
bonuses for which you have sufficient fuel will be applied - for example, if
your hoard is configured to 50% Defence and 50% Damage, and you have enough
silver but not quite enough gold, you will only get the Defence bonus.

Note that you may also add gems to your hoard: rubies, pearls, sapphires, onyx,
emeralds and diamonds give the same fuel as gold, silver, copper, bronze, brass
and platinum respectively.  No other material types can be added to your hoard.

### Scaling
Treasure Hoard, like many dragon powers, uses a scaling for bonuses - meaning that the first few points often give a bigger bonus than the later points. By default you'll have a scale of +1/1/1/1/1, meaning that each point gives a flat bonus of +1, but you can permanently increase this scale by adding different types of item to your hoard (legendary, mythical, relic and artifact).

For example, if you add a legendary gold item, your scaling will be +2/1/1/1/1 for all gold bonuses. If you then add a relic, the scaling will increase to +3/2/1/1/1. Once you've added all four types (in any order), the scaling will reach the maximum of +5/4/3/2/1, meaning the first point gives a +5 bonus, the second point gives +4, the third +3, the fourth +2, and all others +1.

By typing hoard scale you'll be able to see which which types of magic items you still need to collect for each material type. For example it might show something like the following:

\- | -
--- | ---
Gold | You need one artifact.
Silver | You have already collected all four item types for this fuel.
Copper | You need one legendary, one mythical, one relic and one artifact.
Bronze | You need one legendary, one mythical, one relic and one artifact.
Brass | You need one legendary, one mythical, one relic and one artifact.
Platinum | You need one legendary, one mythical, one relic and one artifact.

In the above table, the dragon has already collected a legendary, mythical and relic made from gold, and a legendary, mythical, relic and artifact made from silver, but nothing for any of the other metal types. Thus the dragon would have a +4/3/2/1/1 scale for gold bonuses (damage and power), a +5/4/3/2/1 scale for silver bonuses (defence and protection), and a +1/1/1/1/1 scale for all other bonuses.

### Configuration
Each bonus has a specified cost, and the point total cannot exceed 100. For example damage costs 10% per point, so you could in theory have 10 points in damage (giving +10 damage with no scaling bonus, or 5+4+3+2+1+1+1+1+1+1 = +20 damage with the top scaling bonus). Typing hoard will show how you've set up your bonus, and also allow you to modify it. For example it might show the following:

\- | -
--- | ---
Attack | 5 at 5% per point gives a +5 bonus, using 25% of your Hoard.
Defence | 0 at 5% per point gives a +0 bonus, using 0% of your Hoard.
Health | 15 at 1% per point gives a +15 bonus, using 15% of your Hoard.
Damage | 5 at 10% per point gives a +11 bonus, using 50% of your Hoard.
Resistance | 0 at 8% per point gives a +0 bonus, using 0% of your Hoard.
Speed | 0 at 12% per point gives a +0 bonus, using 0% of your Hoard.
Ascendancy | 0 at 4% per point gives a +0 bonus, using 0% of your Hoard.
Protection | 0 at 4% per point gives a +0 bonus, using 0% of your Hoard.
Power | 0 at 8% per point gives a +0 bonus, using 0% of your Hoard.
Mana | 0 at 2% per point gives a +0 bonus, using 0% of your Hoard.

\- | - | - | - | - | -
--- | --- | --- | --- | --- | ---
Heat | +1 (using 10%) | Cold | +0 (using 0%) | Shock | N/A
Physical | N/A | Mental | +0 (using 0%) | Poison | N/A

In the above tables, 25% of the hoard is being applied to attack, giving a +5 bonus (because of no scaling bonus), 15% is being applied to health, giving a +15 bonus (once again because of no scaling bonus), 50% is being applied to damage, giving a +11 bonus (because of the +4/3/2/1/1 scaling bonus), and the last 10% is being used to give a +1 heat bypass bonus (the bypass bonuses do not get scaled).

This adds up to a total of 100%, representing the overall bonus per rank. Thus at rank 10, the above setup would give +50 attack, +150 health, +110 damage and +10 heat bypass.

Note that attack, ascendancy, defence, protection, health and mana are further modified by your green magic, which is applied as a percentage bonus. Using the above setup once again, an age 100 character with 10 ranks and 100 in green magic would actually get +100 attack, +300 health, +110 damage and +10 heat bypass.

### Fuel
Each time you draw upon your hoard (either to activate it or to renew the duration) you will have to pay the fuel cost. Each fuel type is used for different bonuses, as follows:

\- | -
--- | ---
Gold (and rubies) | Damage, Power, Heat bypass.
Silver (and pearls) | Defence, Protection, Cold bypass.
Copper (and sapphires) | Speed, Shock bypass.
Bronze (and oynx) | Attack, Ascendancy, Poison bypass.
Brass (and emeralds) | Health, Mana, Physical bypass.
Platinum (and diamonds) | Resistance, Mental bypass.

Typing hoard fuel will also show how much fuel of each type you've got and how much of each is required for your current setup, as well as what scaling and bypass bonuses you've currently unlocked. For example you might see something like the following:

\- | - | - | - | - | -
--- | --- | --- | --- | --- | ---
Gold | 1674.01 fuel, 3.00 required. | Scale | +4/3/2/1/1 | Bypass | +1
Silver | 5002.00 fuel, 0.00 required. | Scale | +5/4/3/2/1 | Bypass | +1
Copper | 0.00 fuel, 0.00 required. | Scale | +1/1/1/1/1 | Bypass | +0
Bronze | 0.00 fuel, 1.25 required. | Scale | +1/1/1/1/1 | Bypass | +0
Brass | 0.00 fuel, 0.75 required. | Scale | +1/1/1/1/1 | Bypass | +0
Platinum | 49984.00 fuel, 0.00 required. | Scale | +1/1/1/1/1 | Bypass | +2

As is clear from the above, the dragon has insufficient fuel to power the bronze and brass bonuses (which in this case are attack and health respectively). The dragon has unlocked +1 bypass bonuses for gold (heat) and silver (cold) as well as a +2 bypass for platinum (mental), but has only selected the +1 heat bypass bonus (using 10% of the hoard) and thus wouldn't benefit from the cold or mental bypass.

The amount of fuel depends on the distibution of your bonuses, but will always add up to 1 fuel per rank. For example if you have 5 points in damage (using 50% of your hoard) then it would require 0.5 gold fuel per rank, while 5 points in attack (using 25% of your hoard) would require 0.25 bronze fuel per rank and 5 points in defence (using 25% of your hoard) requires 0.25 silver fuel per rank. At rank 10, such a setup would use 10 fuel, of which 5 would be gold, 2.5 bronze and 2.5 silver.

You cannot activate your hoard if you lack the fuel to do so. However you can later renew it without the fuel, but you won't gain any of the bonuses related to the fuel type you're lacking (it won't just use what you've got - even if you're just a little short, you won't get any of the bonus for that fuel type).
