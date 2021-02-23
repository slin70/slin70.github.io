---
permalink: /publications/
layout: archive
title: "Publications"
author_profile: true
---


## Book Chapters

* S Lin, Z. Zhou, Z. Zhang, X. Chen, and J. Zhang, "Edge Intelligence in the Making: Optimization, Deep Learning, and Applications", Morgan & Claypool Publishers, 2021.


## Preprints





## Conference Papers




## Jounal Papers



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
