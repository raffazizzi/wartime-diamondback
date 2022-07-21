---
layout: page
title: Beyer, Johanna (1888-1944)
category: incipits
century: 19th
permalink: /beyer/
---
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Johanna_Beyer" target="_blank">https://en.wikipedia.org/wiki/Johanna_Beyer</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
    //Type in the last name and first name of the composer, as above//
      {% if item.author == "Beyer, Johanna" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
