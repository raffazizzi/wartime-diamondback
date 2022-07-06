---
layout: page
title: Negrón, Angélica (1981-)
category: incipits
century: 20th
permalink: /negron/
---

*Learn more about this composer at <a href="https://www.angelicanegron.com/" target="_blank">https://www.angelicanegron.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Negrón, Angélica" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
