---
layout: page
title: Incipit Index
permanlink: /incipit-index/
---

<div class="toc">
  <p>Composer's last names appear in alphabetical order. All of the current incipits are transcribed from scores housed in the Lilly Music Library.</p>
  <p>This page is under development. Incipits will be added here over time and we will be testing out organization and layout.</p>

<ul>
    {% for doc in site.docs %}
      {% if doc.category == "incipits" %}
        <li class="text-title">
          <a href="{{ site.baseurl }}{{ doc.url }}">
        {{ doc.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
