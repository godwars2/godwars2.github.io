---
layout: class
title: Dragon
description: Dragons are an ancient and powerful race of Nephilim, and come in many shapes and forms.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

### Build Basics

Scaled powers (see '[scaling]({{ site.baseurl }}{% link help/scaling.md %}) '), gains bonuses from valuable metals,
fairly customisable, can choose to focus on either heat, cold, shock, poison or
mental (both as offence and defence).  Forms: human, draconian and dragon.

If you don't know where to start, consider getting one of the following:

1. Draconic Rage, Extended Rage, Berserker Rage and a Dragon Descendant.
2. Winds of the Mind, Serenity, Martial Gnosis and a Style Mastery.

Then focus on one of the following power/talent combinations:

1. Human Form, Dragon Mount, Dragonbone Forging and Dragonscale Crafting.
2. Draconian Form, Salamanders Gift and Chameleonic Gift.
3. Dragon Form, any 1 Lord power, and either Treasure Hoard or Dragon Barding.

If you go the Dragon Form route, you'll almost always want Natural Fortitude.

You should also train up the damage-oriented power that corresponds to your
Dragon Descendant talent (eg Fires of the Volcano and Red Dragon Descendant).

### Subclass Tree
<div class="clt">
{% for subclass in site.data.dragon_subclasses %}
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
