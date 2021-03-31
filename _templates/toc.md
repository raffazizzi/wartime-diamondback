---
layout: page
title: Table of Contents example
permalink: /toc/
---
    
   <div class="toc">
  <h2>sample texts</h2>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Backer-Grøndahl, Agathe" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
