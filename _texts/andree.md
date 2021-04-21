---
layout: page
title: Andrée, Elfrida (1841-1929)
category: incipits
century: 19-20th
permalink: /andree/
---
<a title="Elfrida-Andree, IMSLP" href="https://imslp.org/wiki/File:Elfrida-Andree.jpg#filelinks"><img width="256" alt="Andrée, Elfrida" src="https://imslp.org/images/thumb/6/68/Elfrida-Andree.jpg/334px-Elfrida-Andree.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Elfrida_Andr%C3%A9e" target="_blank">https://en.wikipedia.org/wiki/Elfrida_Andr%C3%A9e</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Andrée, Elfrida" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
