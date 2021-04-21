---
layout: page
title: Andrée, Elfrida (1841-1929)
category: incipits
century: 19th
permalink: /andree/
---
<a title="Unknown authorUnknown author, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Andr%C3%A9e,_Elfrida_i_VJ_6_1916.jpg"><img width="256" alt="Andrée, Elfrida i VJ 6 1916" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Andr%C3%A9e%2C_Elfrida_i_VJ_6_1916.jpg/256px-Andr%C3%A9e%2C_Elfrida_i_VJ_6_1916.jpg"></a>

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
