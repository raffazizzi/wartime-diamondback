---
layout: page
title: Incipit Index
permanlink: /incipit-indexv2/
---
This index is under development and additional composers and works will be added. Details about this project are available on this [page](https://annakijas1.github.io/rebalancing-music-canon/about/).

Composer's names appear in alphabetical order and are organized chronologically by century of their birth. Incipits are transcribed from scores housed in the Lilly Music Library, unless otherwise noted. Incipits are being added regularly and there may be titles in the index that do not yet have a corresponding incipit.

<div class="toc">

<h3>Solo Instrument</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.medium == "solo" %}
          <li class="text-author.text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.author }}
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

<h3>Chamber Music</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.medium == "chamber" %}
          <li class="text-author.text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.author }}
         {{ item.title }}
              </a>
    <li>
      {% endif %}
    {% endfor %}
</ul>


</div>
