---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

As a researcher in the Laboratory of Geoinformatics and Geospatial Information Infrastructure, my research 
covers the many faces of geospatial data acquisition, analysis, visualization and utilization. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
