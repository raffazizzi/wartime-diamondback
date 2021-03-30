---
layout: page
---

Beach, Amy Marcy Cheney (1867-1944)
<div>
{% assign text_list = site.texts1 | sort:"url" %}
<ul>
{% for node in text_list %}
  {% if node.title != null and node.url != "/404.html" %}
    <li><a class="sidebar-nav-item{% if page.url == node.url %} active{% endif %}" href="{{ site.baseurl }}{{ node.url }}">{{ node.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
</div>
