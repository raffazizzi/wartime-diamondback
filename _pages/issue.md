---
layout: page
title: The diamondback, Vol. 35, No. 10-A, 1943-12-17
permalink: /1943-12-17/
---

## Articles in the collection

Selection of articles from *The diamondback (College Park, Md.), 1943-12-17*
See full issue on the [University Library website](https://www.lib.umd.edu/univarchives/student-newspapers/id/fbe8564d-426c-456b-aff2-b19c0caaaeb8)

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