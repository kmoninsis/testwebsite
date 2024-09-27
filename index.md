---
layout: default
---

This is some text about the works of Simon Niks.

{% for project in site.projects %}
## {{ project.name }}

### {{ project.type }}

Date: {{ project.date }}

Some text about this project.

{% endfor %}

