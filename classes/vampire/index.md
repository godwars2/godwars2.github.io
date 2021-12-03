---
layout: class
title: Vampire
description: Vampires are a parasitic form of Revenant who have returned from the dead to drink the blood of the living.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

### Build Basics

Strong defence, very stealthy, decent psionics, focuses on cold-based
energy.  Can use heavy bloodsteel armour or weightless shadowsteel armour (but
not both).  Forms: human, cloud of bats, mist and wolf (and later, giant bat).

If you don't know where to start, select one of the following:

1. Blood Legacy and Blood Potency.
2. Rage of the Beast, Extended Rage and Berserker Rage.
3. Mind Magic, Serenity, Mind Over Matter, Martial Gnosis and a Style Mastery.

Then focus on one of the following power/talent combinations:

1. Bat Form, House NightWing, Venom and Evasion.
2. Wolf Form, Claws of the Wolf, Lupine Fortitude, Sure Footed and Evasion.
3. Mist Form, Shadow Crafting, Path of Shadows and House ShadowSworn.
4. Blood Runes, Blood Forging, Armour Proficiency and Heavy Armour Expert.
5. Shadow Crafting, Blade of Darkness, Assassin Training and House DarkBlade.

### Subclass Tree
<div class="clt">
{% for subclass in site.data.vampire_subclasses %}
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
