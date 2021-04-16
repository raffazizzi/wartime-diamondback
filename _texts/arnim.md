---
layout: page
title: Arnim, Bettina von (1785-1859)
category: incipits
century: 18th
permalink: /arnim/
---
<a title="Ludwig Emil Grimm, † 4. April 1863, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Bettina-von-arnim-grimm.jpg"><img width="256" alt="Bettina-von-arnim-grimm" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Bettina-von-arnim-grimm.jpg/256px-Bettina-von-arnim-grimm.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Bettina_von_Arnim" target="_blank">https://en.wikipedia.org/wiki/Bettina_von_Arnim</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Arnim, Bettina von" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
