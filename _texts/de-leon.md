---
layout: page
title: de Leon, Mario Diaz (1979-)
category: incipits
century: 20th
permalink: /de-leon/
---
*Learn more about this composer at <a href="http://mariodiazdeleon.com/" target="_blank">http://mariodiazdeleon.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "de Leon, Mario Diaz" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
