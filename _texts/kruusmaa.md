---
layout: page
title: Kruusmaa, Alisson (1992-)
category: incipits
century: 20th
permalink: /kruusmaa/
---

*Learn more about this composer at <a href="http://alissonkruusmaa.com/" target="_blank">http://alissonkruusmaa.com/</a>*
<br/>


### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Kruusmaa, Alisson" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
