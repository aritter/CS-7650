---
layout: home
title: CS 7650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

- [Piazza](https://piazza.com/class/kj7vngax6ni7lt)
- [Gradescope](https://www.gradescope.com/courses/218786)

{% for module in site.modules %}
{{ module }}
{% endfor %}
