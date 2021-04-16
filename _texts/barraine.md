---
layout: page
title: Barraine, Elsa (1910-1999)
category: incipits
century: 20th
permalink: /barraine/
---
<a title="Unattributed, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Elsa_Barraine_1940.jpg"><img width="256" alt="Elsa Barraine 1940" src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Elsa_Barraine_1940.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Elsa_Barraine" target="_blank">https://en.wikipedia.org/wiki/Elsa_Barraine</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Barraine, Elsa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
