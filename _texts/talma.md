---
layout: page
title: Talma, Louise (1906-1996)
category: incipits
century: 20th
permalink: /talma/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Louise_Talma" target="_blank">https://en.wikipedia.org/wiki/Louise_Talma</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Talma, Louise" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
