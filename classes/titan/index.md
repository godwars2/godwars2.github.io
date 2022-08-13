---
layout: class
title: Titan
description: Titans are a powerful race of elder deities, born from the primal forces of the universe.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

Titans gain various innate bonuses based on their total power ranks, regardless of the actual distribution of those ranks, as follows:

- +1 Speed per rank (up to 2*max rank) and half that bonus to Speed Cap.
- +2 Attack and Defence per rank (up to 5*max rank).
- +1 Damage and Resistance per rank (up to 5*max rank).
- +1% Health per two ranks (up to 4*max rank).
- +1% immunity vs all damage types per rank (up to 1*max rank). 30% max
- +1 physical bypass per rank (up to 3*max rank).
- +1 energy and mental bypass per three ranks (up to 3*max rank).
- +2% natural armour vs all damage types per rank (up to 4*max rank).

Note that if you are wearing armour, half of its soak will be subtracted from the above natural armour bonus, although this cannot reduce it below 0%.

### Build Basics

Titans become increasingly powerful as their potential increases, regardless of
the actual powers selected, so your choices aren't too important.  However you 
should always consider investing a few ranks in each of the following:

1. Mighty Leap allows you to travel, aiding exploration (and escapes).
2. Rapid Healing allows you to heal much faster, and regrow lost limbs.
3. Tremor Sense allows you to sense power surges and locate other players.

### Subclass Tree
<div class="clt">
{% for subclass in site.data.titan_subclasses %}
  <strong>{{ subclass.name }}</strong> <em>({{ subclass.age }})</em>
  {% assign alpha_list = subclass.subclasses %}
  <ul>
    {% for alpha_class in alpha_list %}
    <li>
      <strong>{{ alpha_class.name }}</strong> <em>({{ alpha_class.age }})</em>
      {% assign beta_list = alpha_class.subclasses %}
      <ul>
        {% for beta_class in beta_list %}
        {% assign gamma_list = beta_class.subclasses %}
        {% for gamma_class in gamma_list %}
        <li>
          <strong>{{ beta_class.name }}</strong> <em>({{ beta_class.age }})</em> - <strong>{{ gamma_class.name }}</strong> <em>({{ gamma_class.age }})</em>
        </li>
        {% endfor %}
        {% endfor %}
      </ul>
    </li>
    {% endfor %}
  </ul>
  {% endfor %}
 </div>

### Tips

Titans are considered a “miniclass”, and differ in a significant way from the older five “full” classes.

“Full” classes are designed to allow a wide variety of character build styles (high or low armour, caster, fighter or semi-caster, and a variety of available “forms”). Titans do not have any powers that significantly enhance their spellcasting abilities, so are likely to always remain “fighter” type characters. They only have two forms, human and giant, and the giant form does not change their capabilities significantly (other than affecting their stats).

However, Titans get the innate bonuses based on total power ranks, which means no particular choice of powers leads to an inherently inferior character. For this reason, Titans are a good choice for beginning players.
