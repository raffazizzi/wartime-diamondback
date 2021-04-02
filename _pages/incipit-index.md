---
layout: page
title: Incipit Index
permanlink: /incipit-index/
---
<p>This index is under development and additional composers and works will be added.</p>

  <p>Composer's names appear in alphabetical order and are organized chronologically under the century of their birth. Incipits are transcribed from scores housed in the Lilly Music Library, unless otherwise noted. </p>

<div class="toc">
  <h3>19th-century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "19th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

  <h3>20th-century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "20th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
