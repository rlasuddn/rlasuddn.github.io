---
title: "CarryDuo"
layout: archive
permalink: categories/carryduo
author_profile: true
types: posts
---

{% assign posts = site.categories['carryduo']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
