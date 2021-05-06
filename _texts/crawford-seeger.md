---
layout: page
title: Crawford Seeger, Ruth (1901-1953)
category: incipits
century: 20th
permalink: /crawford-seeger/
---
<a title="Unknown authorUnknown author, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Ruth_Crawford_Seeger.jpg"><img width="128" alt="Ruth Crawford Seeger" src="https://upload.wikimedia.org/wikipedia/commons/9/90/Ruth_Crawford_Seeger.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Ruth_Crawford_Seeger" target="_blank">https://en.wikipedia.org/wiki/Ruth_Crawford_Seeger</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Crawford Seeger, Ruth" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
