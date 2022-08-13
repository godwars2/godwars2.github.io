---
layout: page
title: Spells
---

{% assign pages_list = site.pages %}{% for node in pages_list %}{% if node.title != null %}{% if node.layout == "spell" %}- [{{ node.title }}]({{ site.baseurl }}{{ node.url }})
{% endif %}{% endif %}{% endfor %}
