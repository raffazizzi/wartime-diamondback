---
layout: page
title: Simon, Carlos (1984-)
category: incipits
century: 20th
permalink: /simon/
---

*Learn more about this composer at <a href="http://coliversimon.com/" target="_blank">http://coliversimon.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Simon, Carlos" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
