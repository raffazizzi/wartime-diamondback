---
layout: page
title: Simon, Carlos (1984-)
category: incipits
time-period: 21st century
permalink: /simon/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Simon, Carlos" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
