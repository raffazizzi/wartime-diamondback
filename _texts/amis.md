---
layout: page
title: Amis, Kenneth (1970-)
category: incipits
century: 20th
permalink: /amis/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Kenneth_Amis" target="_blank">https://en.wikipedia.org/wiki/Kenneth_Amis</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Amis, Kenneth" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
