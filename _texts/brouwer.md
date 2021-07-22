---
layout: page
title: Brouwer, Leo (1939-)
category: incipits
century: 20th-21st
permalink: /brouwer/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Leo_Brouwer" target="_blank">https://en.wikipedia.org/wiki/Leo_Brouwer</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Brouwer, Leo" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
