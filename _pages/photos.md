---
layout: archive
permalink: /photos/
title: "Photos"
author_profile: false
---
{% for post in site.categories.photo %}
 {% include archive-single.html type="grid" %}
{% endfor %}
