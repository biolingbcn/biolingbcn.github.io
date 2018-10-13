---
layout: page
title: Who are we?
permalink: /about/
---

We are PhD students of the Biolinguistics Initiative Barcelona, a research group at the University of Barcelona led by Cedric Boeckx. We are from different countries and we have different ages, genders, hair colours, body types, diets, and academic/non-academic interests. Here, we would like to express our personal views on the things that we deal with in our life as PhD students.

### Want to know more? 

Visit our research group's [website](http://bioling.ub.edu).

{% for person in site.people %}
<img src="{{ person.photo }}" align="right" width="10%" style="border-radius: 50%"> <b> {{ person.name }} </b><a href="https://twitter.com/{{ person.twitter }}" target="_blank"><i class="fab fa-twitter"></i></a>
{{ person.content }}
{% endfor %}

### Send us a nice email!

[biolinguistics.bcn@gmail.com](mailto:biolinguistics.bcn@gmail.com)
