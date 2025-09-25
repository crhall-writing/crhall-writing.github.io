---
layout: page
title: poems
permalink: /poems/
---

<ul class="list-plain">
  {% assign items = site.poems | sort: "date" | reverse %}
  {% for p in items %}
    <li><a class="list-link" href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %}
</ul>
