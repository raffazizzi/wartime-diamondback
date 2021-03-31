---
layout: page
title: Barraine, Elsa (1910-1999)
permalink: /barraine-incipits/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Barraine, Elsa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
