---
layout: page
title: Explore by category or author
permalink: /archive
---
<h2>Academia</h2>
{% for post in site.academia %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}

{% endfor %}

<h2>Fun</h2>
{% for post in site.fun %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}

{% endfor %}
