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

My research interests include **Embodied AI**, **Robot Learning**, **Self-Evolving Agents**, and **Vision-Language Models**. I am particularly interested in enabling AI agents to learn from interaction, accumulate reusable experience, and improve the design and control of physical systems.

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
          M.Eng. in Electrical and Computer Engineering; research advised by <a href="https://robotics.umich.edu/profile/xiaonan-huang/" target="_blank"><em>Prof. Xiaonan Huang</em></a>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/southeast.png" alt="Southeast University logo" class="experience-logo">
      <div class="experience-info">
          <strong>Southeast University</strong><br>
          <em>2026.01 - 2026.03</em><br>
          Research Assistant advised by <em>Prof. Chuhan Shi</em>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/shanghaitech.png" alt="ShanghaiTech University logo" class="experience-logo">
      <div class="experience-info">
          <strong>ShanghaiTech University</strong><br>
          <em>2021.09 - 2025.07</em><br>
          B.Eng. in Computer Science, GPA: 3.69/4.0, Rank: 19/180; research advised by <em>Prof. Yang Wang</em> and <em>Prof. Xin Lou</em>
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
        <i style="font-size: 13px;">
          <strong>Yunfei Wang*</strong>,
          Xiaohao Xu*&Dagger;,
          Yang Li,
          Xiaonan Huang
        </i><br>
        We present AUTO-ROBOTIST, a self-evolving LLM agent that distills evaluated successful and failed morphology-search experience into an auditable skill library with ADD, DIAGNOSE, and MERGE operations, achieving a 1.47&times; average convergence speedup on seven 5&times;5 EvoGym tasks and outperforming GA on all seven 10&times;10 cross-scale transfer tasks.
        <br>
        <b><i style="color:#83a1c7;">EMNLP 2026 Main Conference &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2605.25832" target="_blank"><em>[arXiv]</em></a>
        <a href="https://doi.org/10.48550/arXiv.2605.25832" target="_blank"><em>[DOI]</em></a>
      </div>
    </div>
  </div>
</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">EMNLP 2026</span>
      <span class="pub-list-title">When Search Becomes Memory: Accelerating Robot Design Discovery with Self-Evolving Skills</span><br>
      <span class="pub-list-authors"><strong>Yunfei Wang*</strong>, Xiaohao Xu*&Dagger;, Yang Li, Xiaonan Huang</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.25832" target="_blank">[arXiv]</a><a href="https://doi.org/10.48550/arXiv.2605.25832" target="_blank">[DOI]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Awards
--------
- *2024.12*, Merit Student (Top 15%), School of Information Science and Technology.
- *2023.12*, Outstanding Student (Top 5%), School of Information Science and Technology.
