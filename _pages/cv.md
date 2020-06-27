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
* BA Geography, University of Cambridge, 2017
* MSc Remote Sensing, University College London, 2018
* PhD Geography, University of Nottingham, 2022 (expected)

Work experience
======
* January/February 2019: Consultant for Namibian National Leopard Survey 
  * Created a methodology to scale up local camera trap density estimates nationwide, using SPACECAP and Machine Learning
  * Produced a national density estimate and density rasters to inform conservation policy
  
Skills
======
* Proficient in Python, R, and experience in JavaScript
* Experienced in Geospatial analysis
  * Machine Learning (primarily tree-based learners)
  * Geospatial software including QGIS, ArcMap and Google Earth Engine
  * Manipulating, processing and storing large (global) datasets

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
