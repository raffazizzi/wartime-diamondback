---
layout: page
title: Boulanger, Lili (1893-1918)
category: incipits
century: 19-20th
permalink: /boulanger-l/
---
<a title="unidentified photographer, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Lili_Boulanger_1.jpg"><img width="128" alt="Lili Boulanger 1" src="https://upload.wikimedia.org/wikipedia/commons/d/da/Lili_Boulanger_1.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Lili_Boulanger" target="_blank">https://en.wikipedia.org/wiki/Lili_Boulanger</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Boulanger, Lili" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
