---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! I am a master's student in Electrical and Computer Engineering at the University of Michigan (2025.08 - 2026.12).

My research interests broadly include **Embodied AI**, **Robot Learning**, and **AI Agents**, as well as other emerging areas in AI. I enjoy exploring diverse research directions and collaborating with researchers across different fields.

I am currently seeking **research assistant positions**, as well as **Ph.D. opportunities for Fall 2027**.

Feel free to reach out if you are interested in collaboration or potential opportunities.

News
---------------
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.08</em></span> 🎉🎉 Our paper <a href="https://arxiv.org/abs/2605.25832" target="_blank"><em>When Search Becomes Memory: Accelerating Robot Design Discovery with Self-Evolving Skills</em></a> was accepted to EMNLP 2026 Main Conference.</li>
    <li><span class="news-date"><em>2025.08</em></span> 🎓🎓 I began my M.Eng. studies at the University of Michigan.</li>
    <li><span class="news-date"><em>2025.07</em></span> 🎓🎓 I received my B.Eng. degree from ShanghaiTech University.</li>
  </ul>
</div>

Experience
--------------

<div class="experience-container">

  <div class="experience-card">
      <img src="images/umich.png" alt="University of Michigan logo" class="experience-logo">
      <div class="experience-info">
          <strong>University of Michigan</strong><br>
          <em>2025.08 - 2026.12</em><br>
          M.Eng. in Electrical and Computer Engineering & Research Assistant in the <a href="https://soft.robotics.umich.edu/" target="_blank"><em>HDR Lab</em></a> advised by <a href="https://scholar.google.com/citations?user=MNKU_WcAAAAJ&amp;hl=zh-CN" target="_blank"><em>Prof. Xiaonan Huang</em></a>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/southeast.png" alt="Southeast University logo" class="experience-logo">
      <div class="experience-info">
          <strong>Southeast University</strong><br>
          <em>2026.01 - 2026.04</em><br>
          Research Assistant advised by <a href="https://shichuhan.github.io/" target="_blank"><em>Prof. Chuhan Shi</em></a>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/shanghaitech.png" alt="ShanghaiTech University logo" class="experience-logo">
      <div class="experience-info">
          <strong>ShanghaiTech University</strong><br>
          <em>2021.09 - 2025.07</em><br>
          B.Eng. in Computer Science, GPA: 3.69/4.0, Rank: 19/180
      </div>
  </div>

</div>

Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">
  <div class="publication-card" data-category="all">
    <div style="display: flex; align-items: center;">
      <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
        <img src="images/autorobotist-pipeline.png" alt="Auto-Robotist pipeline overview" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
      </div>
      <div>
        <strong>When Search Becomes Memory: Accelerating Robot Design Discovery with Self-Evolving Skills</strong><br>
        <i class="pub-authors">
          <strong class="self-author">Yunfei Wang*</strong>,
          Xiaohao Xu*&Dagger;,
          Yang Li,
          Xiaonan Huang
        </i><br>
        We present AUTO-ROBOTIST, a self-evolving LLM agent that distills evaluated successful and failed morphology-search experience into an auditable skill library with ADD, DIAGNOSE, and MERGE operations.
        <br>
        <span class="pub-venue">EMNLP 2026 Main Conference</span>
        <a class="pub-link" href="https://arxiv.org/abs/2605.25832" target="_blank">[arXiv]</a>
        <a class="pub-link" href="https://github.com/wangyf9/Auto-Robotist" target="_blank">[code]</a>
      </div>
    </div>
  </div>
</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">EMNLP 2026</span>
      <span class="pub-list-title">When Search Becomes Memory: Accelerating Robot Design Discovery with Self-Evolving Skills</span><br>
      <span class="pub-list-authors"><strong class="self-author">Yunfei Wang*</strong>, Xiaohao Xu*&Dagger;, Yang Li, Xiaonan Huang</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.25832" target="_blank">[arXiv]</a><a href="https://github.com/wangyf9/Auto-Robotist" target="_blank">[code]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Videos
--------------
<article class="video-card" aria-labelledby="auto-robotist-video-title">
  <video class="featured-video" controls playsinline preload="none" width="1906" height="1080" poster="{{ '/images/auto-robotist-video.jpg' | relative_url }}" aria-label="Auto-Robotist research video">
    <source src="{{ '/assets/videos/auto-robotist.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support embedded video. <a href="{{ '/assets/videos/auto-robotist.mp4' | relative_url }}">Watch the video directly</a>.
  </video>
  <div class="video-details">
    <div class="video-meta">Research overview <span aria-hidden="true">&middot;</span> 1 min 52 sec</div>
    <h3 id="auto-robotist-video-title">Auto-Robotist</h3>
    <p>See how a self-evolving agent turns robot design experience into reusable skills.</p>
    <div class="video-links">
      <a href="https://arxiv.org/abs/2605.25832" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">&nearr;</span></a>
      <a href="https://github.com/wangyf9/Auto-Robotist" target="_blank" rel="noopener noreferrer">Code <span aria-hidden="true">&nearr;</span></a>
    </div>
  </div>
</article>

Awards
--------
- *2024.12*, Merit Student (Top 15%), School of Information Science and Technology.
- *2023.12*, Outstanding Student (Top 5%), School of Information Science and Technology.
