---
layout: page
title: Projects
subtitle: My things
---
<p>I have really only made one thing that I can actually share buttttttttt here is the list of things!</p>


{% for project in site.data.projects.projects %}
<h3>{{ project.title }}</h3>
<p><a href="{{project.link}}">Link to Project</a></p>
{{ project.description }}
{% endfor %}