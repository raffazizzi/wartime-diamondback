---
layout: page
title: Incipit Index
permalink: /incipit-index/
---

This page is under development. Incipits will be added here over time and we will be testing out organization and layout.

<div class="toc">
  <h2>Incipit Index</h2>
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

