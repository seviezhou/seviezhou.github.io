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
* Ph.D in Computer Science, The Hong Kong University of Science and Technology (HKUST), 2024 (expected)
* B.S. in Computer Science, Beijing Jiaotong University (BJTU), 2019

Work experience
======
* Spring 2018: Security Researcher Intern
  * GXuanwu Lab, Tencent
  * Duties included: Broswer Security
  
Skills
======
* Programming Skills: Python, C/C++, Assembly, PHP, HTML, JavaScript, Go.
* Language Skills: Chinese (Native), English (CET-6: 600, IELTS: 7.5).

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
* External Reviewer:
  * ASE'2022, ISSTA'2023, CCS'2024, ICSE'2024, ISSTA'2024
