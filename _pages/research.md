---
permalink: /
title: "Research"
excerpt: "Research projects"
author_profile: true
redirect_from: 
  - /research/
  - /research.html
---

{% include base_path %}

{% for post in site.research.current %}
  {% include archive-single.html %}
{% endfor %}
