---
layout: page
title: Agnesi, Maria Teresa (1720-1795)
category: incipits
century: 18th
permalink: /agnesi/
---
<a title="Sailko, CC BY 3.0 &lt;https://creativecommons.org/licenses/by/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Anonimo,_ritratto_della_compositrice_e_clavicembalista_maria_teresa_agnesi.jpg"><img width="256" img align="middle" alt="Anonimo, ritratto della compositrice e clavicembalista maria teresa agnesi" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/Anonimo%2C_ritratto_della_compositrice_e_clavicembalista_maria_teresa_agnesi.jpg/256px-Anonimo%2C_ritratto_della_compositrice_e_clavicembalista_maria_teresa_agnesi.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Maria_Teresa_Agnesi_Pinottini" target="_blank">https://en.wikipedia.org/wiki/Maria_Teresa_Agnesi_Pinottini</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Agnesi, Maria Teresa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
