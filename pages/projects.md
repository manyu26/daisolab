---
layout: page
show_meta: false
title: "Research Projects"
subheadline: "Some of my research projects"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/research/projects/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>