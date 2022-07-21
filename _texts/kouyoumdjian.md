---
layout: page
title: Kouyoumdjian, Mary (1983-)
category: incipits
century: 20th
permalink: /kouyoumdjian/
---

*Learn more about this composer at <a href="https://www.marykouyoumdjian.com/" target="_blank">https://www.marykouyoumdjian.com/</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Kouyoumdjian, Mary" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
