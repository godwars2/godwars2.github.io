---
layout: page
title: Talents
---

One of the most important aspects of building an effective character in God Wars
2 is selecting effective combinations of talents. Talents are the special
characteristics of your Supernaturali that makes him/her differ from any other
one of their chosen class. They grant varying abilities, and can be combined
in a variety of ways to create truly god-like powers. They have limits as to
how they can be combined, so choose them wisely. You can drop and add them at
will on your home plane, with some restrictions for Subclass Talents.

You may add a talent to your character by typing 'talent add <talent name>', as
long as you have a free slot.  You start with three talent slots, and earn a
fourth by mastering (i.e., getting to 100) five skills (any of core skills,
weapons and magic).  You earn a fifth talent slot when you master your first
super fighting style.  You also earn a free Weapon Mastery talent by mastering
five weapon skills, a second Weapon Mastery talent by mastering eight weapon
skills, and a third Weapon Mastery talent by mastering all ten weapon skills.

Classed characters also gain a new talent at age 100, another at age 200, etc.

Name|Description
---|---
{% assign pages_list = site.pages %}{% for node in pages_list %}{% if node.title != null %}{% if node.layout == "talent" %}[{{ node.title }}]({{ site.baseurl }}{{ node.url }}) | {{ node.description }}
{% endif %}{% endif %}{% endfor %}
