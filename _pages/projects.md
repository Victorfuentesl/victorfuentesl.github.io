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


 
 <h1 style="font-size:2em; font-weight:bold;"> Universidad de Valparaiso </h1> 

 During the year 2020 - 2021 I taught the following subjects
 
    Calculus I for careers of Bachelor of Science mention Biology, Chemistry, Bachelor of Physics, Eng. in Statistics and Bachelor in Mathematics
    
    Euclidean Geometry for Mathematics Degree
    

 During 2019 I taught the following subjects
 
    Calculus II for Civil Industrial Engineering degree at the Pontifical Catholic University of Valparaíso, Chile.
