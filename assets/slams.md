---
layout: page
title: slams
permalink: /slams/
---

<ul class="list-plain">
  {% assign items = site.slams | sort: "title" %}
  {% for s in items %}
    <li><a class="list-link" href="{{ s.url }}">{{ s.title }}</a></li>
  {% endfor %}
</ul>
