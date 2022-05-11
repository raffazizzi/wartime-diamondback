---
layout: page
title: Bonds, Margaret (1913-1972)
category: incipits
century: 20th
permalink: /bonds/
---
<a title="Carl Van Vechten
, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Margaret_Bonds.jpg"><img width="256" alt="Margaret Bonds" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Margaret_Bonds.jpg/256px-Margaret_Bonds.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Margaret_Bonds" target="_blank">https://en.wikipedia.org/wiki/Margaret_Bonds</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Bonds, Margaret" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
