---
layout: page
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project }}
    </a>
  </h2>
{% endfor %}

