---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into two main areas: scientific computing, mainly
to be able to solve physics problems involving partial differential equations.
More specifically, I'm very interested in computational fluid dynamics.
The second area is applications of Machine Learning to scientific computing.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
