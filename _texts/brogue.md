---
layout: page
title: Brogue, Roslyn (1919-1981)
category: incipits
century: 20th
permalink: /brogue/
---

*Learn more about this composer at <a href="https://dl.tufts.edu/concern/eads/nc580z13w/fa" target="_blank">Roslyn Brogue Henning Papers, 1919-1996</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Brogue, Roslyn" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
