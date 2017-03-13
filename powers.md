---
layout: page
title: Powers
---

A power is a special ability available to Supernaturalis of a certain class.
It cannot be increased through use, only by the expenditure of Primal.  Like
talents, each character has a limited number of available powers.

You may have a number of points in your powers equal to your (Age*Age)/1000,
however your three highest powers don't count towards this total.  Further, no
power may have more ranks than your Age/10 (rounded down).  Thus as an age 100
character you could have 3 powers at 10, and another 10 points distributed
however you please.

Name|Description
---|---
{% assign pages_list = site.pages %}{% for node in pages_list %}{% if node.title != null %}{% if node.layout == "power" %}[{{ node.title }}]({{ site.baseurl }}{{ node.url }}) | {{ node.description }}
{% endif %}{% endif %}{% endfor %}
