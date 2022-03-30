---
layout: page
title: Cheatham, Wallace (1945-2021)
category: incipits
century: 20th
permalink: /cheatham/
---

*Learn more about this composer at <a href="https://composers.com/wallace-cheatham" target="_blank">https://composers.com/wallace-cheatham</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Cheatham, Wallace" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
