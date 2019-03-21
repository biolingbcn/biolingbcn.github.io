---
layout: page
title: Explore by category or author
permalink: /archive
---

<h2>Academia</h2>

{% for post in site.posts %}

{% if post.tag == "academia" %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}

{% endif %}

{% endfor %}

<h2>Evolution</h2>

{% for post in site.posts %}

{% if post.tag == "evolution" %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}

{% endif %}

{% endfor %}


<h2>Recommendations</h2>

{% for post in site.posts %}

{% if post.tag == "recommendations" %}

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> by {{ post.author }}

{% endif %}

{% endfor %}


