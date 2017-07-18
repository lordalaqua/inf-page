---
layout: index
title: Projetos
permalink: /projects/
---

Aqui tem uma lista de projetos que eu desenvolvi durante a graduação. Alguns desses eu fiz quando estava ainda no início da faculdade, então não posso dizer que me orgulho da qualidade da engenharia de software, apesar de sempre me orgulhar do resultado do trabalho de acordo com o meus conhecimentos na época.

<ul>
{%for project in site.projects %}
   <li> 
   <a href="{{project.url}}">{{project.title}}</a> <span>({{project.year}})</span>
   <p>{{project.description}}</p>
   </li>
{% endfor %}
</ul>

