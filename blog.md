---
layout: page
title: "Blog"
permalink: "/blog/"
description: "Notes by Mike Riess on applied AI, large language models, agentic systems and process monitoring."
---

Occasional notes on applied AI, language models, agentic systems and process monitoring. Subscribe via the [RSS feed](/feed.xml).

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: site.date_format }}</time></p>
    <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 220 }}</p>
  </li>
{% endfor %}
</ul>
