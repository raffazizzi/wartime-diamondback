---
layout: page
title: Incipit Index
permalink: /incipit-index/
---

<div class="toc">
  <p>This page is under development. Incipits will be added here over time and we will be testing out organization and layout.</p>
  <ul class="texts">
  {% for item in site.texts %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>

