---
layout: archive
title: "Side Projects"
permalink: /side-projects/
author_profile: true
---
{% include base_path %}

I've been learning web scraping in Python. You can find samples of my work on this page.
{% for post in site.side-projects reversed %}
  {% include archive-single.html %}
{% endfor %}
