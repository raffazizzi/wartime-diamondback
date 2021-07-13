---
layout: page
title: Tailleferre, Germaine (1892-1983)
category: incipits
century: 19-20
permalink: /tailleferre/
---
<a title="Photo by Aldona, CC BY-SA 4.0 via IMSLP" href="https://imslp.org/images/e/e2/G_Tailleferre.png"><img width="128" alt="Germaine Tailleferre" src="https://imslp.org/images/e/e2/G_Tailleferre.png"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Germaine_Tailleferre" target="_blank">https://en.wikipedia.org/wiki/Germaine_Tailleferre</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Tailleferre, Germaine" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
