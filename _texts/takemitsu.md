---
layout: page
title: Takemitsu, Tōru (1930-1996)
category: incipits
century: 20th
permalink: /takemitsu/
---

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Tōru_Takemitsu" target="_blank">https://en.wikipedia.org/wiki/Tōru_Takemitsu</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Takemitsu, Tōru" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
