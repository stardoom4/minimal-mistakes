---
permalink: /
title: "Wunder"
layout: single
author_profile: true
sidebar:
  nav: "sidebar"
header:
  overlay_image: /assets/images/header-img.jpg
  overlay_filter: 0.4 
---
<h3>Recents</h3>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
