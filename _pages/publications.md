---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* Brain Network Analysis
  * Performed structural analysis on human connectome and chimpanzee connectome data.
  * Implemented graphical measures such as centralities, motifs, clustering coefficients, max-flow, analysis of unique edges, etc. among others, and showcased differences between the two brain networks.