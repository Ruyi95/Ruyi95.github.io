---
layout: project
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
### [{{ project.name }}]({{ project.url }}) ###
#### {{ project.starttime }} {% if project.endtime %} - {{ project.endtime }}{% endif%} ####

<p> {{ project.excerpt }}</p>

{% endfor %}

