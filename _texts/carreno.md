---
layout: page
title: Carreño, Teresa (1853-1917)
category: incipits
century: 19th
permalink: /carreno/
---
<a title="National Portrait Gallery
, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Teresa_Carre%C3%B1o_(negative).jpg"><img width="256" alt="Teresa Carreño (negative)" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Teresa_Carre%C3%B1o_%28negative%29.jpg/256px-Teresa_Carre%C3%B1o_%28negative%29.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Teresa_Carre%C3%B1o" target="_blank">https://en.wikipedia.org/wiki/Teresa_Carreño</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Carreño, Teresa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
