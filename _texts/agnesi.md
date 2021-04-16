---
layout: page
title: Agnesi, Maria Teresa (1720-1795)
category: incipits
century: 18th
permalink: /agnesi/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Agnesi, Maria Teresa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
