---
layout: page
title: Brouwer, Leo (1939-)
category: incipits
century: 20th-21st
permalink: /brouwer/
---

<a title="me, CC BY-SA 3.0 &lt;http://creativecommons.org/licenses/by-sa/3.0/&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Leob.jpg"><img width="128" alt="Leob" src="https://upload.wikimedia.org/wikipedia/commons/a/aa/Leob.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Leo_Brouwer" target="_blank">https://en.wikipedia.org/wiki/Leo_Brouwer</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Brouwer, Leo" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
