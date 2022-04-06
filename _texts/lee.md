---
layout: page
title: Lee, James, III (1975-)
category: incipits
century: 20th
permalink: /lee/
---

*Learn more about this composer at <a href="https://www.jameslee3music.com/biography" target="_blank">https://www.jameslee3music.com/biography</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Lee, James, III" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
