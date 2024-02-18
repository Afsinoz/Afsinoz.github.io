---
layout: archive
title: "Publications and Reports"
permalink: /publications/
author_profile: true
---
## Under Construction 
Some blog posts are on the way, then we can discuss on wide variety of topics. 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
