---
layout: page
title: Eastman, Julius (1940-1990)
category: incipits
century: 20th
permalink: /eastman/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Julius_Eastman" target="_blank">https://en.wikipedia.org/wiki/Julius_Eastman</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Eastman, Julius" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
