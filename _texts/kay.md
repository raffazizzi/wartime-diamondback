---
layout: page
title: Kay, Ulysses (1917-1995)
category: incipits
century: 20th
permalink: /kay/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Ulysses_Kay" target="_blank">https://en.wikipedia.org/wiki/Ulysses_Kay</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Kay, Ulysses" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
