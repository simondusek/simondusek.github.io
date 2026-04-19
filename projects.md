---
title: Projects
subtitle: Portfolio of data analytics work
---

This page highlights practical projects focused on SQL, Python, and Power BI.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: site.date_format }}
{% endfor %}
