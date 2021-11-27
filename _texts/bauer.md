---
layout: page
title: Bauer, Marion (1882-1955)
category: incipits
century: 19th
permalink: /bauer/
---
<a title="Unknown authorUnknown author, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:MarionBauer1922.jpg"><img width="256" alt="MarionBauer1922" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/MarionBauer1922.jpg/256px-MarionBauer1922.jpg"></a>
*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Marion_Bauer" target="_blank">https://en.wikipedia.org/wiki/Marion_Bauer</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Bauer, Marion" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
