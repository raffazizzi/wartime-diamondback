---
layout: page
title: "Incipit Index"
permanlink: /main-index/
---

<div class="toc">

<h3>Getting Started</h3>
<ul>
    {% for item in site.pages %}
      {% if item.category == "incipits" %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
</div>
