---
layout: page
title: Ustvolskaya, Galina (1919-2006)
category: incipits
century: 20th
permalink: /ustvolskaya/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Galina_Ustvolskaya">https://en.wikipedia.org/wiki/Galina_Ustvolskaya</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ustvolskaya, Galina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
