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


Selected Publications
=====
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
