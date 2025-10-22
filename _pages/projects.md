---
layout: page
title: Projects
permalink: /projects/
description: A growing collection of your cool projects.
nav: true
nav_order: 2
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">

{% assign sorted_projects = site.projects | sort: "importance" | limit: 4 %}

<!-- Generate cards for each project -->
{% if page.horizontal %}
<div class="container">
  <div class="row row-cols-1 row-cols-md-2">
  {% for project in sorted_projects %}
    {% include projects_horizontal.liquid %}
  {% endfor %}
  </div>
</div>
{% else %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>
{% endif %}

</div>
