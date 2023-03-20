---
title: "TypeScript"
layout: archive
permalink: categories/typescript
author_profile: true
types: posts
---

{% assign posts = site.categories['typescript']%}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
