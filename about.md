---
layout: page
title: Who are we?
permalink: /people/
---

Welcome to the personal blog of the [Cognitive Biology of Language](http://bioling.ub.edu) research group. We're from the University of Barcelona and the group is headed by [Cedric Boeckx](http://bioling.ub.edu/index.php/people/cedric-boeckx/). We decided to write this blog to have a more casual medium to express our thoughts on the work we do, both related to its content as well as the challenges that surround it. Our idea is to make this a space to freely mix serious academic issues with more easily digestible content. If you want to share any thoughts on any of the topics discussed here, we're very much looking forward to hearing from you in the comments section. You can also write to us or visit us on Twitter!

{% for person in site.people %}
<img src="{{ person.photo }}" align="right" width="10%" style="border-radius: 50%"> <b> {{ person.name }} </b><a href="https://twitter.com/{{ person.twitter }}" target="_blank"><i class="fab fa-twitter"></i></a>
{{ person.content }}
{% endfor %}

### Send us a nice [email](mailto:biolinguistics.bcn@gmail.com)!


