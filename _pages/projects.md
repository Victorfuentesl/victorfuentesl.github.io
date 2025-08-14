---
layout: page
title: Teaching
permalink: /teaching/
description:  A growing collection of lectures notes I worked on. Check them out!
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


 <h1 style="font-size:2em; font-weight:bold;"> Université de Bretagne Occidentale </h1> 

Spring 2025	- Real Analysis (L1 Mathematics), UBO Brest, 30h Tutorials.


---
 
 <h1 style="font-size:2em; font-weight:bold;"> Universidad de Valparaiso </h1> 

 During the year 2020 - 2021 I taught the following subjects
 
  -Calculus 1 (L1 Biology, Chemistry, Bachelor of Physics, Statistics and Mathematics)
  
  -Euclidean Geometry (L1 Mathematics)
  
---

 During 2019 I taught Calculus 2 (Civil Industrial Engineering) at the Pontifical Catholic University of Valparaíso, Chile.
