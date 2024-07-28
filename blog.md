---
layout: page
title: "Research blog"
mathjax: true
permalink: "/blog/"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Research notes" %}
{% endif %}
