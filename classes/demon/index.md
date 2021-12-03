---
layout: class
title: Demon
description: Demons are powerful Nephilim, dark and twisted beings from another dimension who feed upon fear and pain.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

### Build Basics

If you don't know where to start, select one of the following:

1. Demonic Rage, Extended Rage, Berserker Rage and Devil Spawn.
2. Protean Nemesis, Serenity and a Style Mastery (may also add Martial Gnosis).

Then decide whether you want to play in either demon or human form:

1. Demon Form, Infernal Forging (or an unarmoured skin warp) and Tainted Flesh.
2. Ritual Scarring, Infernal Forging, Tainted Flesh and Warbeast.

You want at least 1 rank in Bladed Tail, Spiked Tail or Venomous Tail.  If you 
are fighting unarmed get Tainted Talons, otherwise consider Infernal Binding.

For protection, Armour Proficiency and Heavy Armour Expert can work well. If 
you're using Demon Form you could instead use Toughness with Natural Fortitude
or perhaps Tough Hide with Strong Magical Shields.

### Subclass Tree
<div class="clt">
{% for subclass in site.data.demon_subclasses %}
  <strong>{{ subclass.name }}</strong> <em>({{ subclass.age }})</em>
  {% assign alpha_list = subclass.subclasses %}
  <ul>
    {% for alpha_class in alpha_list %}
    <li>
      <strong>{{ alpha_class.name }}</strong> <em>({{ alpha_class.age }})</em>
      {% assign beta_list = alpha_class.subclasses %}
      <ul>
        {% for beta_class in beta_list %}
        <li>
          <strong>{{ beta_class.name }}</strong> <em>({{ beta_class.age }})</em>
          {% assign gamma_list = beta_class.subclasses %}
          <ul>
            {% for gamma_class in gamma_list %}
            <li>
              <strong>{{ gamma_class.name }}</strong> <em>({{ gamma_class.age }})</em>
            </li>
            {% endfor %}
          </ul>
        </li>
        {% endfor %}
      </ul>
    </li>
    {% endfor %}
  </ul>
  {% endfor %}
 </div>
