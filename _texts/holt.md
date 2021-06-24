---
layout: page
title: Holt, Nora Douglas (1884/5-1974)
category: incipits
century: 19-20th
permalink: /holt/
---

<a title="Carl Van Vechten, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Portrait_of_Nora_Holt_by_Carl_Van_Vechten.jpg"><img width="256" alt="Portrait of Nora Holt by Carl Van Vechten" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/Portrait_of_Nora_Holt_by_Carl_Van_Vechten.jpg/256px-Portrait_of_Nora_Holt_by_Carl_Van_Vechten.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Nora_Holt" target="_blank">https://en.wikipedia.org/wiki/Nora_Holt</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Holt, Nora Douglas" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
