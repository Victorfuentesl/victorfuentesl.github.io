---
layout: page
title: Teaching
permalink: /teaching/
description: “Mathematics, rightly viewed, possesses not only truth, but supreme beauty—a beauty cold and austere, like that of sculpture, without appeal to any part of our weaker nature, without the gorgeous trappings of painting or music, yet sublimely pure, and capable of a stern perfection such as only the greatest art can show.”
Bertrand Russell
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
published: true
---

<!-- pages/projects.md -->
<div class="projects">
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
</div>
