---
layout: page
title: Day, Kevin (1996-)
category: incipits
century: 20th
permalink: /day/
---
*Learn more about this composer at <a href="https://www.kevindaymusic.com/" target="_blank">https://www.kevindaymusic.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Day, Kevin" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
