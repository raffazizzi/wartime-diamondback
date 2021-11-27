---
layout: page
title: Szymanowska, Maria (1789-1831)
category: incipits
century: 18th
permalink: /szymanowska/
---
<a title="Deutsch: Gemälde im Musée Mickiewicz in Paris (1932)., Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Maria_Szymanowska.jpg"><img width="256" alt="Maria Szymanowska" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Maria_Szymanowska.jpg/256px-Maria_Szymanowska.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Maria_Szymanowska" target="_blank">https://en.wikipedia.org/wiki/Maria_Szymanowska</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Szymanowska, Maria" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
