---
layout: page
title: Lizée, Nicole (1973)
category: incipits
century: 20th
permalink: /lizee/
---

<a title="Photo of composer Nicole Lizee on a video shoot in 2019. CC SA 4.0 https://upload.wikimedia.org/wikipedia/commons/0/00/Nicole_Lizee_Film_Set.jpg"><img width="256" alt="Photo of composer Nicole Lizee on a video shoot in 2019" src="https://upload.wikimedia.org/wikipedia/commons/0/00/Nicole_Lizee_Film_Set.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Nicole_Lizée" target="_blank">https://en.wikipedia.org/wiki/Nicole_Liz%C3%A9e</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Lizée, Nicole" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
