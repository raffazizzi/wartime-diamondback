---
layout: page
title: Price, Florence B. (1887-1953)
category: incipits
century: 19-20th
permalink: /price/
---

<a title="Florence B. Price" href="https://i.pinimg.com/736x/09/6e/eb/096eeb13d7787a2b2682851c7489833f--composers-orchestra.jpg"><img width="256" img align="middle" alt="Florence B. Price" src="https://i.pinimg.com/736x/09/6e/eb/096eeb13d7787a2b2682851c7489833f--composers-orchestra.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Florence_Price" target="_blank">https://en.wikipedia.org/wiki/Florence_Price</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Price, Florence B." %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
