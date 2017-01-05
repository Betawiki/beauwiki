---
layout: page
permalink: /categories/Découpe_laser
title: Découpe laser
---

{% for post in site.categories.Découpe_laser %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}