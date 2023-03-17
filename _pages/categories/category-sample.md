---
title: "블로그 샘플"
layout: archive
permalink: categories/sample
author_profile: true
types: posts
---

{% assign posts = site.categories['sample']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
