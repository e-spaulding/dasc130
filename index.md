---
layout: home
title: Home/Schedule
nav_exclude: false
nav_order: 1
permalink: /:path/
---

# DASC130: Introduction to Data Science

Welcome!

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}