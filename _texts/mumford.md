---
layout: page
title: Mumford, Jeffrey (1955-)
category: incipits
century: 20th
permalink: /mumford/
---
*Learn more about this composer at <a href="https://www.jeffreymumford.com/">https://www.jeffreymumford.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Mumford, Jeffrey" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
