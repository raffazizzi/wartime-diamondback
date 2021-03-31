---
layout: page
title: Esmail, Reena
category: incipits
permalink: /esmail/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Esmail, Reena" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
