---
layout: class
title: Werewolf
description: Werewolves are a form of Lycanthrope, infused with great physical strength and power.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

### Build Basics

Very fast, good attack, powerful bursts (see 'help burst'), focuses
on shock-based energy.  Can use moonweave clothing and weightless moonsilver
weapons/armour in human form.  Forms: human, wolfman and wolf.

If you don't know where to start, select one of the following:

1. Spirit of Fenris, Extended Rage, Berserker Rage and Desert Wolfkin.
2. Self Control, Serenity and a Style Mastery (may also add Martial Gnosis).
3. Fang Forging, Faith, Berserker Rage and Tireless Rage.

Then focus on one of the following power/talent combinations:

1. Moon Weaving, Lunar Forging, Spirit Binding, Sure Footed and Evasion.
2. Self Control, Fang Forging, Lupine Fortitude and Natural Fortitude.
3. Wolf Form, Talons of the Bear, Lupine Fortitude, Sure Footed and Evasion.
4. Ride the Storm, Greater Crow Spirit, Spirit Wolfkin and Enhanced Deflection.

### Subclass Tree
<div class="clt">
{% for subclass in site.data.werewolf_subclasses %}
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
