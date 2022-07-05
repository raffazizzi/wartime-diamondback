---
layout: page
title: Montgomery, Jessie (1981-)
category: incipits
century: 20th
permalink: /montgomery/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Jessie_Montgomery" target="_blank">https://en.wikipedia.org/wiki/Jessie_Montgomery</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Montgomery, Jessie" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
