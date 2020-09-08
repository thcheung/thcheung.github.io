---
layout: archive
title: 'Projects'
permalink: /projects/
author_profile: true
click: false
---

{% include base_path %}

{% for post in site.projects reversed %}
{% include archive-project.html %}
{% endfor %}
