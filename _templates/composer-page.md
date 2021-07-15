---
layout: page
title: Last Name, First Name (Dates)
category: incipits
century: number
permalink: /lastname/
---
//if the composer has a wikipedia page and there is an image, click on the image and then more details to view the file. Go to "use this file on the web" to view the embed code and then insert it below//

//insert embed code to public domain image here, if available//

//insert the wikipedia link below in the two spots as identified//
*Learn more about this composer at <a href="insert link to wikipedia or composer website" target="_blank">insert the same link as before</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
    //Type in the last name and first name of the composer, as above//
      {% if item.author == "Last Name, First Name" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
