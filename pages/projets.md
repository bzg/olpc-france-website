---
layout: page
show_meta: false
title: "Nos projets"
subheadline: "Nos projets actifs pour 2016"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/projets/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
