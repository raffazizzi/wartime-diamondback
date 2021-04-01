---
layout: page
title: Incipit Index
permanlink: /incipit-index/
---
<p>This index is being developed. Additional composers and works will be added.</p>

  <p>Composer's namees appear in alphabetical order and chronologically under the century when they were born. Incipits are transcribed from scores housed in the Lilly Music Library, unless otherwise noted. </p>

<div class="toc">
  <h3>Composers born in the 19th-century</h3>
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

  <h3>Composers born in the 20th-century</h3>
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
