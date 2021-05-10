---
layout: page
title: Assandra, Caterina (1590?-1618?)
category: incipits
century: 16-17th
permalink: /assandra/
---
<a title="Caterina Assandra, CC BY-SA 4.0" href="https://imslp.org/wiki/Category:Assandra,_Caterina"><img width="256" img align="middle" alt="Assandra, Caterina" src="https://imslp.org/images/thumb/7/70/Assandra%2C_Caterina.jpg/232px-Assandra%2C_Caterina.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Caterina_Assandra" target="_blank">https://en.wikipedia.org/wiki/Caterina_Assandra</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Assandra, Caterina" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>