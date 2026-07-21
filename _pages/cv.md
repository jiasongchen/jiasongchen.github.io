---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can also download my CV [here](/files/cv.pdf).

Education
======

* B.S. in Mathematics, University of Denver, 2017
* M.S. in Computer Science, University of Denver, 2019
* Ph.D in Computer Science, University of Miami, 2026 (expected)

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
