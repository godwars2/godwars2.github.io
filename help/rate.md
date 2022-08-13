---
layout: help
title: rate
---

Your movement rate is calculate in fps (feet per second), as follows:

\- | 
--- | ---
Walking rate | (Size/3) + 3 - Encumbrance Level + (Athletics/100) + Misc.
Jogging rate | (Size/3) + 10 - (Encumbrance Level * 2) + (Athletics/50) + Misc.
Running rate | (Size/3) + 20 - (Encumbrance Level * 4) + (Athletics/25) + Misc.
Mounted walking rate | 10 + (Riding/100) + Misc.
Mounted jogging rate | 20 + (Riding/50) + Misc.
Mounted running rate | 40 + (Riding/25) + Misc.

Your Encumbrance Level is 0 if you are unencumbered, 1 for light encumbrance, 2
for medium encumbrance and 3 for heavy encumbrance.

Misc refers to any bonuses from powers, magic items and spells.  The end result
is then capped at 66.  Penalties from wounds are applied after the cap, so that
if you've been hamstrung in one leg, your movement rate can never exceed 61.

Different terrain types may also apply a penalty: -1 for deserts, ice or rocky 
ground, -2 for mountains, forests and swamps, -3 when wading in shallow water, 
-4 for swimming in deep water, and -5 for quicksand, whirlpools and lava.
