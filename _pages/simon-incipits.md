---
layout: page
title: Simon, Carlos
permalink: /simon-incipits/
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
