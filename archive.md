---
layout: page
title: Archive
permalink: /archive
---
{% for post in site.posts %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}


{% endfor %}
