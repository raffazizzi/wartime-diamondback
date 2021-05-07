---
layout: page
title: Incipit Index
permanlink: /incipit-index/
---
This index is under development and additional composers and works will be added. Details about this project are available on this [page](https://annakijas1.github.io/rebalancing-music-canon/about/).

Composer's names appear in alphabetical order and are organized chronologically by century. Incipits are transcribed from scores housed in the Lilly Music Library, unless otherwise noted. 

<div class="toc">
  <h3>16-17th centuries</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "16-17th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
  
  <h3>17th century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "17th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

<h3>18th century</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "18th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
  
   <h3>18-19th centuries</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "18-19th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

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

 <h3>19-20th centuries</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "19-20th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

  <h3>20th century</h3>
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

 <h3>20th-21st centuries</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "20th-21st" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
