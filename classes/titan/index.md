---
layout: class
title: Titan
description: Titans are a powerful race of elder deities, born from the primal forces of the universe.
---

### [Powers](powers) - [Talents](talents) - [Subclasses](subclasses)

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
