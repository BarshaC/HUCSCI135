---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Computer Science I (Python)
---
{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## About the Class

About the course

See the [Syllabus page](syllabus.md) for more details on course policies.

## Course Materials
{% for module in site.modules %}
{{ module }}
{% endfor %}