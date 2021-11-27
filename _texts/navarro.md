---
layout: page
title: Navarro, Johanny (1992-)
category: incipits
century: 20th
permalink: /navarro/
---

*Learn more about this composer at <a href="https://johannynavarro.com/" target="_blank">https://johannynavarro.com/</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Navarro, Johanny" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
