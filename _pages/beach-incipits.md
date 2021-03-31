---
layout: page
title: Beach, Amy Marcy Cheney (1867-1944)
permalink: /beach-incipits/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Beach, Amy Marcy Cheney" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
