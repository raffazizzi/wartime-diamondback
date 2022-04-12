---
layout: page
title: Agócs, Kati (1975-)
category: incipits
century: 20th
permalink: /agocs/
---
*Learn more about this composer at <a href="https://www.katiagocs.com/kati-agocs-biography" target="_blank">https://www.katiagocs.com/kati-agocs-biography</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Agócs, Kati" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
