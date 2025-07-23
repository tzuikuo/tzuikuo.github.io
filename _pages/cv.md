---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Fluid Mechanics, Institute of Mechaics, Chinese Academy of Sciences, Jan 2025 
* B.S. in Mathematics, East China Normal University, 2019

Work experience
======
* Jan 2025: Postdoctoral Researcher
  * Institute of Mechaics, Chinese Academy of Sciences
  
Skills
======
* CFD: OpenFOAM, Fluent
* Data Analysis: matlab, python, paraview, tecplot

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
