---
layout: page
title: Beach, Amy Marcy Cheney (1867-1944)
permalink: /beach-incipits/
---

  <p>Composer's last names appear in alphabetical order followed by the title of the composition for which an incipit is available. All of the current incipits are transcribed from scores housed in the Lilly Music Library.</p>
  <p>This page is under development. Incipits will be added here over time and we will be testing out organization and layout.</p>

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Beach, Amy Marcy Cheney" %}
          <li><a href="{{ item.url }}">{{ item.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

