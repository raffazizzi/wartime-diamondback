---
layout: page
title: Perkinson, Coleridge-Taylor (1932-2004)
category: incipits
century: 20th
permalink: /perkinson/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Coleridge-Taylor_Perkinson" target="_blank">https://en.wikipedia.org/wiki/Coleridge-Taylor_Perkinson</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Perkinson, Coleridge-Taylor" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
