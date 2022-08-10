---
layout: help
title: critical
---

Your percentage chance to hit someone is your attack times 100, divided by the 
total of your attack plus your opponent's defence.  For example, if you have 
the same attack as your opponent has defence, you will have a 50% chance of 
hitting them.  If your attack is double your opponent's defence, you will have 
a 66% chance of hitting them.  If your attack is three times your opponent's 
defence, you will have a 75% chance of hitting them.  And so on.

The mud then makes your attack roll by generating a random number between 1 and
100.  If you are using Expert Axeman and roll below 96, the result is reduced 
by 5.  If the roll is 5 or less, your attack is a critical hit.  If the roll is
greater than your chance of hitting, or greater than 95, then the attack fails.

If your attack is successful, it may still be a critical hit.  Calculate your 
accuracy bonus by subtracting 50 from your chance of hitting, to a minimum of 
1.  The percentage success of your attack is equal to your chance of hitting, 
minus your attack roll, plus your accuracy bonus, multiplied by 100 and then 
divided by your chance of hitting.  This percentage success will always be at 
least 1% and never more than 100%.  If it is 100% then you inflict a critical 
hit.  This percentage also indicates how much of your damage you inflict - if 
you hit with a 50% success, you cause half of your maximum damage.
