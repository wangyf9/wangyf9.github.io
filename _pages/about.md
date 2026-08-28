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

Hi! I am a master's student in Electrical and Computer Engineering at the University of Michigan.

My research interests include **Embodied AI**, **Robot Learning**, **Self-Evolving Agents**, and **Vision-Language Models**. I am particularly interested in enabling AI agents to learn from interaction, accumulate reusable experience, and improve the design and control of physical systems.

Feel free to reach out if you are interested in collaboration or potential opportunities.

News
---------------
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.05</em></span> 🎉🎉 Our work <a href="https://arxiv.org/abs/2605.25832" target="_blank"><em>When Search Becomes Memory: Accelerating Robot Design Discovery with Self-Evolving Skills</em></a> is available on arXiv.</li>
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
          <strong>TOOL-EVOLVE: Self-Evolving VLM Agent for Robotic Tool–Action Co-Design</strong><br>
          <em>2026.06 - Present</em><br>
          University of Michigan, advised by <a href="https://robotics.umich.edu/profile/xiaonan-huang/" target="_blank"><em>Prof. Xiaonan Huang</em></a><br>
          <span style="color:#888;">Developing an experience-driven VLM agent with simulator-grounded reflection and cross-task memory for robotic tool–action co-design.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/umich.png" alt="University of Michigan logo" class="experience-logo">
      <div class="experience-info">
          <strong>AUTO-ROBOTIST: Self-Evolving LLM Agent for Robot Design</strong><br>
          <em>2025.12 - 2026.07</em><br>
          University of Michigan, advised by <a href="https://robotics.umich.edu/profile/xiaonan-huang/" target="_blank"><em>Prof. Xiaonan Huang</em></a><br>
          <span style="color:#888;">Built an auditable skill library that converts evaluated robot-design trials into reusable knowledge for cold-start search and cross-scale transfer.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/southeast.png" alt="Southeast University logo" class="experience-logo">
      <div class="experience-info">
          <strong>CrossSense: Interview Agent for Expert–Researcher Semantic Alignment</strong><br>
          <em>2026.01 - 2026.03</em><br>
          Southeast University, advised by <em>Prof. Chuhan Shi</em><br>
          <span style="color:#888;">Developed an HCI interview assistant that detects communication gaps and provides real-time LLM-based support for shared understanding.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/shanghaitech.png" alt="ShanghaiTech University logo" class="experience-logo">
      <div class="experience-info">
          <strong>Biological Fish Motion Reconstruction for Robot Fish Motion Control</strong><br>
          <em>2024.11 - 2025.05</em><br>
          ShanghaiTech University, advised by <em>Prof. Yang Wang</em><br>
          <span style="color:#888;">Built a real-to-sim pipeline for biomimetic imitation learning, including fish pose estimation and automated motion retargeting.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/shanghaitech.png" alt="ShanghaiTech University logo" class="experience-logo">
      <div class="experience-info">
          <strong>Optimization of Neural Rendering with Posit Number System</strong><br>
          <em>2023.06 - 2023.11</em><br>
          ShanghaiTech University, advised by <em>Prof. Xin Lou</em><br>
          <span style="color:#888;">Integrated the Posit number system into NGP's MLP and hash encoding, reducing bit width while preserving reconstruction quality.</span>
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
          Xiaonan Huang.
        </i><br>
        We present Auto-Robotist, a self-evolving LLM agent that distills robot-design search traces into an explicit, auditable skill library and reuses learned skills across tasks and design scales.
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
      <span class="pub-list-authors"><strong>Yunfei Wang*</strong>, Xiaohao Xu*&Dagger;, Yang Li, Xiaonan Huang.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.25832" target="_blank">[arXiv]</a><a href="https://doi.org/10.48550/arXiv.2605.25832" target="_blank">[DOI]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Projects
--------
- **GTRM: Gated Recursive Reasoning with Tiny Networks** — Extended the Tiny Recursion Model with context, attention, and recurrent gating, improving Sudoku reasoning accuracy by 5.6 percentage points.
- **Distributionally Robust Neural Networks on Stable-Diffusion-Generated Data** — Evaluated eight training regimes under controlled, style-based distribution shifts.
- **TEULM: Time-Efficient Ultrasound Localization Microscopy** — Developed a GPU-accelerated reconstruction pipeline using downsampling and 2D spatiotemporal RBF interpolation.

Awards
--------
- *2024.12*, Merit Student (Top 15%), School of Information Science and Technology.
- *2023.12*, Outstanding Student (Top 5%), School of Information Science and Technology.

Skills
--------
- **Languages:** Python, C/C++, MATLAB.
- **Frameworks:** PyTorch.
- **Tools:** Git, Blender, Unity, Linux.
