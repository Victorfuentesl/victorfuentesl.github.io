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


<img src="/assets/img/Banner.gif" alt="banner GIF" width="1080" style="display:block; margin:auto;">

 <h1 style="font-size:2em; font-weight:bold;"> Université de Bretagne Occidentale </h1> 

Spring 2025	- Real Analysis (L1 Mathematics), UBO Brest, 30h Tutorials.


---
 
 <h1 style="font-size:2em; font-weight:bold;"> Universidad de Valparaiso </h1> 

 
  Fall 2020, Spring 2020, Fall 2021, Spring 2021 - Calculus 1 (L1 Biology, Chemistry, Bachelor of Physics, Statistics and Mathematics) [ES Full course videos](https://www.youtube.com/playlist?list=PLuKNSgZVXUiak1B3TEU9p1b8XzN3o06cS)
  
  Fall 2020, Spring 2020, Spring 2021 - Euclidean Geometry (L1 Mathematics) [ES Full course videos](https://www.youtube.com/playlist?list=PLuKNSgZVXUibvUB7_FQb4usqL7KuftbNU)
  
---

 During 2019 I taught Calculus 2 (Civil Industrial Engineering) at the Pontifical Catholic University of Valparaíso, Chile.
