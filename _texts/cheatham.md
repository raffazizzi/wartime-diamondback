---
layout: page
title: Cheatham, Wallace (1945-2021)
category: incipits
century: 20th
permalink: /cheatham/
---

*Learn more about this composer at <a href="https://composers.com/wallace-cheatham" target="_blank">insert the same link as before</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
    //Type in the last name and first name of the composer, as above//
      {% if item.author == "Last Name, First Name" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
