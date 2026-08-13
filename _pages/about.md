---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.ab-grid { display:grid; grid-template-columns: minmax(0,1fr) 240px; gap:2.2rem; align-items:start; }
.ab-news { border-left:1px solid rgba(128,128,128,0.22); padding-left:1.5rem; }
.ab-news-title { font-size:1.2em; font-weight:700; margin-bottom:0.3em; }
.ab-year { font-size:0.95em; font-weight:700; opacity:0.7; margin:1.35em 0 0.55em; padding-bottom:0.3em; border-bottom:1px solid rgba(128,128,128,0.25); }
.ab-year:first-of-type { margin-top:0.4em; }
.ab-news-item { display:flex; align-items:flex-start; gap:11px; padding:5px 0; }
.ab-news-date { flex:0 0 32px; background:rgba(128,128,128,0.14); border-radius:5px; padding:2px 0; text-align:center; font-weight:600; font-size:0.7em; letter-spacing:0.02em; margin-top:2px; opacity:0.85; }
.ab-news-item .n { font-size:0.9em; line-height:1.5; }
.ab-chip { display:inline-block; background:rgba(128,128,128,0.14); border:1px solid rgba(128,128,128,0.3); border-radius:999px; padding:4px 12px; font-size:0.85em; margin:0 5px 6px 0; }
/* Publications */
.pubs-title { font-size:1.4em; font-weight:700; margin:2.2rem 0 0.3rem; padding-bottom:0.3rem; border-bottom:2px solid rgba(128,128,128,0.25); }
.pub { padding:22px 0; border-bottom:1px solid rgba(128,128,128,0.16); }
.pub-thumb { margin:6px 0 14px; }
.pub-thumb img { width:100%; border-radius:10px; border:1px solid rgba(128,128,128,0.2); background:#fff; display:block; }
.pub-venue { display:inline-block; background:rgba(128,128,128,0.16); border-radius:5px; padding:2px 9px; font-size:0.72em; font-weight:700; letter-spacing:0.02em; }
.pub-title { font-weight:700; font-size:1.02em; margin:7px 0 4px; line-height:1.35; }
.pub-authors { font-size:0.88em; opacity:0.75; margin-bottom:9px; }
.pub-authors .me { font-weight:700; opacity:1; }
.pub-links { display:flex; flex-wrap:wrap; gap:7px; }
.pub-links a { font-size:0.9em; font-weight:600; background:#fff; color:#000; border:1px solid rgba(128,128,128,0.4); border-radius:7px; padding:3px 14px; text-decoration:none; }
.pub-links a:hover { background:#eee; text-decoration:none; }
.pub details { margin-top:9px; }
.pub summary { cursor:pointer; font-size:0.8em; font-weight:600; opacity:0.8; list-style:none; }
.pub summary::-webkit-details-marker { display:none; }
.pub summary::before { content:"\25B8  "; }
.pub details[open] summary::before { content:"\25BE  "; }
.pub details p { font-size:0.85em; line-height:1.6; opacity:0.85; margin:8px 0 0; }
@media (max-width: 920px) {
  .ab-grid { grid-template-columns:1fr; gap:1.2rem; }
  .ab-news { border-left:none; padding-left:0; margin-top:0.5rem; }
}
/* This page only: remove the theme's large right gap (susy suffix) so the
   News column reaches the right edge of the content instead of floating mid-page. */
@media screen and (min-width: 925px) {
  .page { padding-right: 0 !important; margin-right: 0 !important; }
}
</style>

<div class="ab-grid">
<div class="ab-main">
<p>I am <strong>Seungwoo Eun</strong>. I work on <strong>3D interaction techniques for Extended Reality (XR)</strong>: how people select and manipulate objects in virtual space, especially content that is far away or at a <strong>scale</strong> that is hard to reach directly.</p>
<p>Much of my work is on <strong>remote interaction</strong>, helping users handle distant objects as easily as nearby ones, even when they differ a lot in <strong>scale</strong>.</p>
<p>I recently finished my <strong>M.S. in Artificial Intelligence</strong> at <strong>Pusan National University</strong> (<a href="https://sites.google.com/view/xrhci/home"><strong>XR Lab</strong></a>, advised by Prof. Myungho Lee), after a <strong>B.S. in Electrical and Computer Engineering</strong> there in 2024. Building on that, I want to bring <strong>AI</strong> into <strong>spatial computing</strong>, designing XR interfaces that read a user's context and intent so that 3D content and its visualization are easier to explore and work with.</p>
<p style="margin:1.3em 0 1.4em;"><span class="ab-chip">XR</span><span class="ab-chip">3D Interaction</span><span class="ab-chip">3D User Interfaces</span><span class="ab-chip">Spatial Computing</span><span class="ab-chip">Visualization</span><span class="ab-chip">HCI</span></p>
<p>I love small talks about <strong>XR</strong>, <strong>3D Interaction</strong>, and <strong>Visualization</strong>! Feel free to <a href="mailto:aglraswe@gmail.com">reach out</a>!</p>

<h2 class="pubs-title">Selected Publications</h2>
<div class="pub">
<div class="pub-body">
<span class="pub-venue">ISMAR 2026</span>
<div class="pub-title">Investigating Scale-Control Strategies for Portal-Based Remote Object Manipulation in Virtual Reality</div>
<div class="pub-thumb"><img src="/images/pub-scale-control.png" alt="Investigating Scale-Control Strategies for Portal-Based Remote Object Manipulation in VR"></div>
<div class="pub-authors"><span class="me">Seungwoo Eun</span>, Isaac Cho, Myungho Lee</div>
<div class="pub-links"><span style="font-size:0.78em; opacity:0.55;">To appear</span></div>
<details><summary>Abstract</summary><p>Portal-based interaction enables users to access and manipulate distant content without physical navigation. However, effective remote manipulation remains challenging due to mismatches between the object and interaction scales, which reduce control precision and increase coordination effort. In this study, we investigate how different scale-management strategies in portal-based interaction affect task performance and user experience in virtual reality (VR). We designed four portal techniques that vary in how interaction scale is controlled during manipulation: fixed-scale, manually scalable, overview+detail, and transfer-based configurations. We conducted a within-subject VR experiment (N = 31) using a remote 6 Degree-of-Freedom (DoF) docking task with objects of varying sizes. Results show that the four strategies differed in manipulation performance, particularly for smaller objects. Multi-portal configurations improved efficiency by providing task-appropriate interaction scales, whereas single-portal approaches offered simpler workflows but required additional user effort. These findings show how scale-management strategies trade off across task phases and provide design guidance for portal-based manipulation in VR.</p></details>
</div>
</div>
<div class="pub">
<div class="pub-body">
<span class="pub-venue">IEEE VR 2026 &middot; Poster</span>
<div class="pub-title">Scalable Portals for Distant Object Manipulation in Virtual Reality</div>
<div class="pub-thumb"><img src="/images/pub-scalable-portals.png" alt="Scalable Portals for Distant Object Manipulation in VR"></div>
<div class="pub-authors"><span class="me">Seungwoo Eun</span>, Isaac Cho, Myungho Lee</div>
<div class="pub-links"><a href="https://ieeexplore.ieee.org/abstract/document/11489658">DOI</a><a href="https://youtu.be/V-wPp6vkI-I">Video</a><a href="/images/Scalable_Portals_Poster.pdf">Poster</a></div>
<details><summary>Abstract</summary><p>Portal-based interaction supports distant object manipulation in Virtual Reality (VR) by bringing remote content into the user's reachable space, but its effectiveness is often limited by sensitivity to object scale. In this work, we examine scalable portal designs that reduce scale-related limitations in portal-based interaction. We explore two designs: a single scalable portal with explicit user control of scale and a dual-portal approach that decouples selection and manipulation through automatic scale normalization. A preliminary pilot user study using a 3D docking task suggests that both scalable portal designs reduce mean task completion time compared to a static portal baseline, particularly for smaller targets, while introducing modest selection overhead.</p></details>
</div>
</div>
<div class="pub">
<div class="pub-body">
<span class="pub-venue">ISMAR 2025</span>
<div class="pub-title">Effects of Peripheral Optic Flow Location and Speed on Unintended Positional Drift during Walk-In-Place in VR</div>
<div class="pub-thumb"><img src="/images/pub-optic-flow.png" alt="Effects of Peripheral Optic Flow on Unintended Positional Drift during Walk-In-Place in VR"></div>
<div class="pub-authors"><span class="me">Seungwoo Eun</span>, Taeyun Noh, Myungho Lee</div>
<div class="pub-links"><a href="https://ieeexplore.ieee.org/abstract/document/11220405/">DOI</a></div>
<details><summary>Abstract</summary><p>Vection can elicit a compelling illusion of self-motion, even when the user remains physically stationary. When combined with user actions, this illusion can enhance the sense of presence in virtual environments. However, vection may unintentionally influence physical locomotion, causing unintended positional drift (UPD). UPD is especially problematic for Walk-In-Place (WIP) navigation in virtual reality (VR), where users simulate locomotion by mimicking walking motions without actual displacement. In this study, we investigated how vection affects UPD during WIP navigation in immersive VR. We specifically manipulated the location of peripheral optic flow (left, right, bilateral) and speed (low, high) using dynamic textures on the lateral walls of the virtual environment to induce various vection conditions. Twenty-seven participants performed WIP under six vection conditions (three locations x two speeds) and one baseline condition without optic flow. Our results revealed that bilateral vection caused the greatest UPD, particularly along the lateral axis, while unilateral vection tended to suppress lateral drift. However, peripheral optic flow speed did not significantly affect UPD. We discuss these findings and their implications for designing immersive virtual environments that mitigate UPD while maintaining the sense of presence.</p></details>
</div>
</div>
</div>
<div class="ab-news">
<div class="ab-news-title">News</div>
<div class="ab-year">2026</div>
<div class="ab-news-item"><span class="ab-news-date">Oct</span><span class="n">🙋 I will attend IEEE ISMAR 2026 as a Student Volunteer</span></div>
<div class="ab-news-item"><span class="ab-news-date">Jun</span><span class="n">🎉 Paper accepted to IEEE ISMAR 2026</span></div>
<div class="ab-news-item"><span class="ab-news-date">Jun</span><span class="n">👥 Attended the KIISE CG&amp;I Workshop</span></div>
<div class="ab-news-item"><span class="ab-news-date">Mar</span><span class="n">🖼️ Presented a poster at IEEE VR 2026</span></div>
<div class="ab-news-item"><span class="ab-news-date">Feb</span><span class="n">🎓 Graduated with an M.S. from the XR Lab, Pusan National University</span></div>
<div class="ab-year">2025</div>
<div class="ab-news-item"><span class="ab-news-date">Dec</span><span class="n">🎉 Poster accepted to IEEE VR 2026</span></div>
<div class="ab-news-item"><span class="ab-news-date">Dec</span><span class="n">🛡️ Completed my M.S. thesis defense</span></div>
<div class="ab-news-item"><span class="ab-news-date">Oct</span><span class="n">🎤 Attended IEEE ISMAR 2025 and presented my paper</span></div>
<div class="ab-news-item"><span class="ab-news-date">Sep</span><span class="n">🎤 Presented "Pitch My Work" (Walk-In-Place) at APMAR 2025</span></div>
<div class="ab-news-item"><span class="ab-news-date">Sep</span><span class="n">🎤 Presented a Scalable Portal paper at APMAR 2025</span></div>
<div class="ab-news-item"><span class="ab-news-date">Jul</span><span class="n">🎉 Paper accepted to IEEE ISMAR 2025</span></div>
<div class="ab-year">2024</div>
<div class="ab-news-item"><span class="ab-news-date">Jun</span><span class="n">👥 Attended the KIISE CG&amp;I Workshop</span></div>
<div class="ab-news-item"><span class="ab-news-date">Mar</span><span class="n">📚 Began my M.S. in the XR Lab, Pusan National University</span></div>
<div class="ab-year">2023</div>
<div class="ab-news-item"><span class="ab-news-date">Nov</span><span class="n">🥉 3rd place, campus Capstone competition (real-time 3D reconstruction pipeline using NeRF)</span></div>
<div class="ab-news-item"><span class="ab-news-date">Mar</span><span class="n">🌱 Joined the XR Lab as an undergraduate research intern</span></div>
</div>
</div>
