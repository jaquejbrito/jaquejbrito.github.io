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
* Ph.D in Computer Science, University of São Paulo, 2017
* Doctorate Sandwich (internship), University of California San Diego (2016-2017)
* M.S. in Computer Science, University of São Paulo, 2012
* B.S. in Physics, University of São Paulo, 2009


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


Other technical experience
======
* Developed conference manager system at Vandroiy (2011-2017)
* Referee for the Brazilian Finals of the IYPT 2015
