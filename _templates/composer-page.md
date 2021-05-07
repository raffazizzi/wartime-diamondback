---
layout: page
title: Last Name, First Name (Dates0
category: incipits
century: number
permalink: /lastname/
---
//insert link to public domain image if available//

*Learn more about this composer at <a href="insert link to wikipedia or composer website" target="_blank">same link as before</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Last Name, First Name" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
