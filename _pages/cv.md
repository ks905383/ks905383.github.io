---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
header:
  text_color: $dark-gray
---

{% include base_path %}

See my [full](../../files/schwarzwald_fullcv_2308.pdf) or [efficient](../../files/schwarzwald_midcv_2308.pdf) CV. 

Education
======
* Bachelor of the Arts (A.B.) in Physics, Public Policy (concentration in Economics), University of Chicago, 2015
* Master of Law in China Studies (concentration in Politics and International Relations), Yenching Academy, Peking University, 2017
* Ph.D in Earth and Environmental Sciences, Columbia University, 2024 (expected)

Selected Publications
=====
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
