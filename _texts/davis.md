---
layout: page
title: Davis, Anthony (1951-)
category: incipits
century: 20th
permalink: /davis/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Anthony_Davis_(composer)" target="_blank">https://en.wikipedia.org/wiki/Anthony_Davis_(composer)</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Davis, Anthony" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
