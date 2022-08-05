---
layout: page
title: Coleman, Valerie (1970-)
category: incipits
century: 20th
permalink: /coleman/
---
*Learn more about this composer at <a href="https://www.vcolemanmusic.com/" target="_blank">https://www.vcolemanmusic.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Coleman, Valerie" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
