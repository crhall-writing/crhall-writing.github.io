---
layout: page
title: scripts
permalink: /scripts/
---

<ul class="list-plain">
  {% assign items = site.scripts | sort: "date" | reverse %}
  {% for s in items %}
    <li><a class="list-link" href="{{ s.url }}">{{ s.title }}</a></li>
  {% endfor %}
</ul>
