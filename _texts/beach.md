---
layout: page
title: Beach, Amy Marcy Cheney (1867-1944)
category: incipits
century: 19th
permalink: /beach/
---

<a title="George Grantham Bain Collection (Library of Congress), Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Amy_Beach_01.jpg"><img width="256" alt="Amy Beach 01" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Amy_Beach_01.jpg/256px-Amy_Beach_01.jpg"></a>

###### Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Amy_Beach" target="_blank">https://en.wikipedia.org/wiki/Amy_Beach</a>

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
