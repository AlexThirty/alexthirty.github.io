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
* Ph.D in Artificial Intelligence, University of Pisa, 2027 (expected)
* M.S. in Mathematics, University of Pisa, 2022
* Master in Mathematics, Scuola Normale Superiore, 2022
* B.S. in Mathematics, University of Pisa, 2020

Work experience
======
* 2022-2023: Data Scientist
  * Electra Vechicles inc.
  * Machine Learning models for fault prediction in electric batteries and smart charging.

Awards
======
* Bronze Medal at International Physics Olympiad (IPhO) 2017
* Gold Medal at the Italian Mathematics Olympiad (ItaMO) 2017
* Gold Medal at the Italian Physics Olympiad 2017
* Silver Medal at the Italian Mathematics Olympiad (ItaMO) 2016
* Bronze Medal at the Italian Physics Olympiad 2016
* Bronze Medal at the Italian Mathematics Olympiad (ItaMO) 2015

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
