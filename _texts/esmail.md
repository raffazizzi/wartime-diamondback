---
layout: page
title: Esmail, Reena (1983-)
category: incipits
century: 20th
permalink: /esmail/
---

<a title="Reema Esmail" href="https://sandrfoundation.org/sites/default/files/images/winners/Reena%20Headshot%202017%20square.jpg"><img width="256" alt="Reema Esmail" src="https://sandrfoundation.org/sites/default/files/images/winners/Reena%20Headshot%202017%20square.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Reena_Esmail" target="_blank">https://en.wikipedia.org/wiki/Reena_Esmail</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Esmail, Reena" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
