---
layout: page
title: Incipit Index
permanlink: /incipit-index/
---

  <p>Composer's last names appear in alphabetical order. All of the current incipits are transcribed from scores housed in the Lilly Music Library.</p>
  <p>This page is under development. Incipits will be added here over time and we will be testing out organization and layout.</p>

<div class="toc">
    <ul class="texts">
    {% for item in site.texts %}
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

