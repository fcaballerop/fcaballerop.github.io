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
* B.S. in Physics, Univ. Complutense, Madrid, 2015
* M.S. in Mathematics and Theoretical Physics, Univ. of Cambridge, UK, 2016
* Ph.D in Mathematics and Theoretical Physics, Univ. of Cambridge, UK, 2020

Publications
======
  See on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
  
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
  
