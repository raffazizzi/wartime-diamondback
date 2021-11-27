---
layout: page
title: Tillis, Frederick C. (1930-2020)
category: incipits
century: 20th
permalink: /tillis/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Frederick_C._Tillis" target="_blank">https://en.wikipedia.org/wiki/Frederick_C._Tillis</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Tillis, Frederick" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
