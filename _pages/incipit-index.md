---
layout: page
title: Incipit Index
permalink: /incipit-index/
---


<div>
{% assign texts_list = site.texts | sort:"url" %}
<ul>
{% for node in texts_list %}
  {% if node.title != null and node.url != "/404.html" %}
    <li><a class="sidebar-nav-item{% if page.url == node.url %} active{% endif %}" href="{{ site.baseurl }}{{ node.url }}">{{ node.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
</div>
