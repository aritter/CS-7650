---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1eZHLhts3HyexqAnc4gXkeIgaywyL0ugmz0B5yphGda0/edit?usp=sharing).

{% for module in site.modules %}
{{ module }}
{% endfor %}
