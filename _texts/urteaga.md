---
layout: page
title: Urteaga, Irma (1929-2022)
category: incipits
century: 20th
permalink: /urteaga/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Irma_Urteaga" target="_blank">https://en.wikipedia.org/wiki/Irma_Urteaga</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Urteaga, Irma" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
