---
layout: page
title: Main Index
permanlink: /main-index/
---

<div class="toc">

<h3>Getting Started</h3>
<ul>
    {% for item in site.pages %}
      {% if item.category == "incipits" %}
        <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
