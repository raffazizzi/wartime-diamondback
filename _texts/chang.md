---
layout: page
title: Chang, Dorothy (1970-)
category: incipits
century: 20th
permalink: /chang/
---
*Learn more about this composer at <a href="https://www.dorothychang.com/" target="_blank">https://www.dorothychang.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Chang, Dorothy" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
