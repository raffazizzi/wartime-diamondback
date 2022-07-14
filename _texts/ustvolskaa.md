---
layout: page
title: Ustvólʹskaâ, Galína (1919-2006)
category: incipits
century: 20th
permalink: /ustvolskaa/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Galina_Ustvolskaya">https://en.wikipedia.org/wiki/Galina_Ustvolskaya</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Ustvólʹskaâ, Galína" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
