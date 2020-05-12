---
layout: archive
title: "Hominin species"
permalink: /hominins/
author_profile: false
---


<ul>
  {% for hominin in site.hominins %}
    <li>
      <h2><a href="{{ hominin.url }}">{{ hominin.title }}</a></h2>
      <p>{{ hominin.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>