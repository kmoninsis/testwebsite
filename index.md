---
layout: default
---

This is some text about the works of Simon Niks.

{% for project in site.projects %}
- [{{ project.title }} - {{ project.date | date: 'yyyy' }}]({{ project.url | relative_url }})
- Test
{% endfor %}

