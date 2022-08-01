---
layout: class
title: Mage
description: Mages are powerful Illuminati who have learned to control and manipulate the elements.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

### Build Basics

Strong magic, superb ranged attacks, decent psionics, item enchantments,
can focus on heat, cold, or shock based energy (but is usually pretty good at
the other two as well).  Forms: human, fire, air, earth, water and ethereal.

If you don't know where to start, select one of the following:

1. Flameborn Adept, Great Burn, and max out Fire Magic.
2. Waterborn Adept, Great Freeze, and max out Water Magic.
3. Windborn Adept, Great Shock, and max out Air Magic.

Make sure you have at least 1 rank in all three of the above Magic powers, so
that you can chain together firebolt, lightning bolt and icebolt.

You should also consider Form of Air or Form of Fire, as they make it much
easier to keep out of your opponent's range.  Form of Air is faster, but Form
of Fire has stronger offensive spell bonuses and can wear metal armour.

Enhanced Deflection and Strong Magical Shields are great for protection, while
the Enchantment power is very useful for adding bonuses to your equipment.

### Subclass Tree
<div class="clt">
{% for subclass in site.data.mage_subclasses %}
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
