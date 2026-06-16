---
layout: page
title: aidan
permalink: /aidan/
---

<ul class="list-plain">
  {% assign items = site.aidan | sort: "date" | reverse %}
  {% for p in items %}
    <li><a class="list-link" href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %}
</ul>
