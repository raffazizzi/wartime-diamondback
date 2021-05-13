---
layout: page
title: Allessandra, Caterina (1700s?)
category: incipits
century: 18th
permalink: /allessandra/
---

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Allessandra, Caterina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>