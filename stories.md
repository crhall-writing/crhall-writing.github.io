---
layout: page
title: stories
permalink: /stories/
---

<ul class="list-plain">
  {% assign items = site.stories | sort: "date" | reverse %}
  {% for s in items %}
    <li><a class="list-link" href="{{ s.url }}">{{ s.title }}</a></li>
  {% endfor %}
</ul>
