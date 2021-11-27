---
layout: page
title: Moore, Dorothy Rudd (1940-)
category: incipits
century: 20th
permalink: /moore/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Dorothy_Rudd_Moore" target="_blank">https://en.wikipedia.org/wiki/Dorothy_Rudd_Moore</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Moore, Dorothy Rudd" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
