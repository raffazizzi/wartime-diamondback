---
layout: page
title: Incipit Index
permalink: /incipit-index/
---

This page is under development. Incipits will be added here over time and we will be testing out organization and layout.

<div>
{% assign text_list = site.texts | sort:"url" %}
<ul>
{% for node in text_list %}
  {% if node.title != null and node.url != "/404.html" %}
    <li><a class="sidebar-nav-item{% if page.url == node.url %} active{% endif %}" href="{{ site.baseurl }}{{ node.url }}">{{ node.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
</div>

<div class="toc">
  <h2>Incipit Index</h2>
  <ul class="texts">
  {% for item in site.texts1 %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>

