---
layout: archive
title: research
permalink: /research/
---
{% include base_path %}
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}