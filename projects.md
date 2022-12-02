---
layout: page
title: Projects
subtitle: My things
---
<p>I have really only made one thing that I can actually share buttttttttt here is the list of things!</p>


{% for project in site.data.projects.projects %}
<h3>{{ project.title }}</h3>
[Link to Project]({{ project.details.link }})
<p>{{ project.details.description }}</p>
{% endfor %}

<!--* Amazon Stock Bot  
[Link to Project](https://github.com/decampc/amazon-stock-bot)\
This project was just a fun thing that I did during the GPU shortage to if I could. I also was bored and wanted to play around with Python/APIs. It takes in an Amazon shopping link and will continuously(and inefficiently) monitor the page for any mention of being in stock for less than a specified price. It works. Not well. -->