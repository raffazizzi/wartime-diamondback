---
layout: page
title: Abels, Michael (1962-)
category: incipits
century: 20th
permalink: /abels/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Michael_Abels" target="_blank">https://en.wikipedia.org/wiki/Michael_Abels</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Abels, Michael" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
