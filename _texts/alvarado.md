---
layout: page
title: Alvarado, Jannet (1963-)
category: incipits
century: 20th
permalink: /alvarado/
---

*Learn more about this composer at <a href="https://www.cayambismusicpress.com/jannet-alvarado-delgado-s/1852.htm" target="_blank">https://www.cayambismusicpress.com/jannet-alvarado-delgado-s/1852.htm</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Alvarado, Jannet" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
