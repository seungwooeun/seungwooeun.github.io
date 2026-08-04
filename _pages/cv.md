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
* Extended Reality (XR): Virtual and Augmented Reality
* 3D User Interfaces and Interaction Techniques
* Spatial Computing
* Visualization
* Human–Computer Interaction (HCI)

Publications
======
  <ul>{% for post in site.publications reversed %}
    <li>{% if post.paperurl %}<a href="{{ post.paperurl }}">{{ post.title }}</a>{% else %}{{ post.title }}{% endif %}. <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}.</li>
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    <li>{{ post.title }}. <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}.</li>
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    <li>{{ post.title }}. <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}.</li>
  {% endfor %}</ul>

Honors and Awards
======
* 3rd place, Campus Capstone Design Competition (real-time 3D reconstruction pipeline using NeRF), Pusan National University, 2023
