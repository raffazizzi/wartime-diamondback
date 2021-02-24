---
layout: page
title: Music Data
permalink: /data/
---

## Needs updating

We are beginning with a small corpus (about 178 pieces) shared by the [Music Theory Examples by Women (MTEW) project](https://musictheoryexamplesbywomen.com/). Their work includes the compilation of excerpts and complete musical compositions by women composers, including women of color. It is used by music theory, history, and performance faculty, and students, as well as secondary music teachers. MTEW has a diverse corpus of music by women from which we can draw, and the data we extract and encode will be made available via their project for greater visibility and reuse.

The list of compositions and composers that will be encoded is drawn from the MTEW project and can be viewed in this [spreadsheet](https://docs.google.com/spreadsheets/d/10BWNZQ0e5EduUB_UBJpDdROjY3VetWvAucYGhnGXaGo/edit#gid=970050992). Extracted data will be checked against the score listed in the spreadsheet and can be found as a PDF on the MTEW site. The music documents (PDF files) can also be shared with interested contributors. We will not store the score PDFs in this repository.


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
