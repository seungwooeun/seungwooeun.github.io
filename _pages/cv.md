---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- CV PDF를 files/ 폴더에 올린 뒤 아래 줄의 주석을 풀면 다운로드 버튼이 생겨:
[Download CV (PDF)](/files/CV.pdf){: .btn .btn--info} -->

Education
======
* M.S. in Artificial Intelligence, Pusan National University, 2026
* B.S. in Electrical and Computer Engineering, Pusan National University, 2024

Research Interests
======
* Virtual and Augmented Reality (VR/AR)
* 3D User Interfaces and interaction techniques
* Object manipulation and locomotion in immersive VR
* Human–Computer Interaction (HCI)
* Immersive visualization

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Awards
======
* 3rd Place, Campus Capstone Design Competition — real-time 3D reconstruction pipeline using NeRF, Pusan National University, 2023
