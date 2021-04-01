---
layout: page
title: Beach, Amy Marcy Cheney (1867-1944)
category: incipits
century: 19th | 20th
permalink: /beach/
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
