---
layout: archive
title: "Articles"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "Record of my life on this beautiful blue planet."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.hack %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
