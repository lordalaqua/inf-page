---
layout: page
title: Projetos
permalink: /projects/
---


{%for project in site.projects %}
   [{{project.title}}]({{project.url}})
{% endfor %}


