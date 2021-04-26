---
layout: page
title: Price, Florence (1887-1953)
category: incipits
century: 19-20th
permalink: /price/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Florence_Price" target="_blank">https://en.wikipedia.org/wiki/Florence_Price/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Price, Florence" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
