---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<section class="hero" aria-labelledby="hero-title">
  <p class="eyebrow">Embodied AI · Robot Learning · Self-Evolving Agents</p>
  <h1 id="hero-title">Turning experience into intelligence.</h1>
  <p class="hero-copy">
    I am a master's student in Electrical and Computer Engineering at the
    <strong>University of Michigan</strong>. My research explores how AI agents can learn from
    interaction, build reusable memory, and improve the design and control of physical systems.
  </p>
  <div class="hero-actions">
    <a class="home-button home-button--primary" href="mailto:wyunfei@umich.edu">Get in touch</a>
    <a class="home-button" href="https://arxiv.org/abs/2605.25832" target="_blank" rel="noopener">Read my paper ↗</a>
    <a class="home-button" href="{{ '/files/Yunfei_Wang_Resume.pdf' | relative_url }}">Download CV</a>
  </div>
  <div class="interest-list" aria-label="Research interests">
    <span>Embodied intelligence</span>
    <span>Vision-language agents</span>
    <span>Robot design</span>
    <span>Experience-driven learning</span>
  </div>
</section>

<h2 id="news" class="section-heading"><span>01</span> News</h2>

<div class="news-box">
  <ul class="news-list">
    <li><time datetime="2026-05">May 2026</time><span>Our work <a href="https://arxiv.org/abs/2605.25832" target="_blank" rel="noopener"><em>When Search Becomes Memory</em></a> is available on arXiv.</span></li>
    <li><time datetime="2025-08">Aug 2025</time><span>Started my M.Eng. in Electrical and Computer Engineering at the University of Michigan.</span></li>
    <li><time datetime="2025-07">Jul 2025</time><span>Graduated from ShanghaiTech University with a B.Eng. in Computer Science.</span></li>
  </ul>
</div>

<h2 id="research" class="section-heading"><span>02</span> Research</h2>

<div class="timeline">
  <article class="timeline-item">
    <div class="timeline-mark">UM</div>
    <div>
      <div class="item-meta">Jun 2026 — Present · University of Michigan</div>
      <h3>TOOL-EVOLVE: Self-Evolving VLM Agent for Robotic Tool–Action Co-Design</h3>
      <p>Developing an experience-driven VLM agent that jointly evolves tool geometry and action strategy, with a simulator-grounded reflector and cross-task memory for transferring reusable capabilities to unseen manipulation tasks.</p>
      <p class="advisor">Advisor: Prof. Xiaonan Huang</p>
    </div>
  </article>

  <article class="timeline-item">
    <div class="timeline-mark">UM</div>
    <div>
      <div class="item-meta">Dec 2025 — Jul 2026 · University of Michigan</div>
      <h3>AUTO-ROBOTIST: Self-Evolving LLM Agent for Robot Design</h3>
      <p>Built an auditable skill library that turns successful and failed morphology-search trials into transferable design knowledge. Across seven EvoGym tasks, the system accelerated cold-start search and transferred from 5×5 to 10×10 design spaces.</p>
      <p class="advisor">Advisor: Prof. Xiaonan Huang</p>
    </div>
  </article>

  <article class="timeline-item">
    <div class="timeline-mark">SEU</div>
    <div>
      <div class="item-meta">Jan 2026 — Mar 2026 · Southeast University</div>
      <h3>CrossSense: Interview Agent for Semantic Alignment</h3>
      <p>Contributed to an HCI interview assistant that detects communication gaps between researchers and domain experts, then provides real-time, LLM-based support for building shared understanding.</p>
      <p class="advisor">Advisor: Prof. Chuhan Shi</p>
    </div>
  </article>

  <article class="timeline-item">
    <div class="timeline-mark">ST</div>
    <div>
      <div class="item-meta">Nov 2024 — May 2025 · ShanghaiTech University</div>
      <h3>Biological Fish Motion Reconstruction</h3>
      <p>Built a real-to-sim pipeline for biomimetic imitation learning, including fish pose estimation from 9,046 annotated frames and automated motion retargeting in Blender and Fish-Gym.</p>
      <p class="advisor">Advisor: Prof. Yang Wang</p>
    </div>
  </article>
</div>

<h2 id="publications" class="section-heading"><span>03</span> Publication</h2>

<article class="publication-card publication-card--featured">
  <div class="paper-visual" aria-hidden="true">
    <div class="robot-grid">
      <i></i><i></i><i class="active"></i><i></i><i></i>
      <i></i><i class="active"></i><i class="active"></i><i class="active"></i><i></i>
      <i class="active"></i><i class="active"></i><i class="core"></i><i class="active"></i><i class="active"></i>
      <i></i><i class="active"></i><i class="active"></i><i class="active"></i><i></i>
      <i></i><i></i><i class="active"></i><i></i><i></i>
    </div>
    <span>search → reflect → remember</span>
  </div>
  <div class="paper-content">
    <div class="item-meta">EMNLP 2026 Main Conference</div>
    <h3>When Search Becomes Memory: Turning Robot Design Trials into Transferable Skills</h3>
    <p class="paper-authors"><strong>Yunfei Wang*</strong>, Xiaohao Xu*, Yang Li, Xiaonan Huang</p>
    <p>We present Auto-Robotist, a self-evolving LLM agent that distills robot morphology-search traces into an explicit, auditable skill library and retrieves that experience to guide future design.</p>
    <p class="paper-note">* Equal contribution</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2605.25832" target="_blank" rel="noopener">arXiv ↗</a>
      <a href="https://doi.org/10.48550/arXiv.2605.25832" target="_blank" rel="noopener">DOI ↗</a>
      <span>Code coming soon</span>
    </div>
  </div>
</article>

<h2 id="projects" class="section-heading"><span>04</span> Selected Projects</h2>

<div class="project-grid">
  <article class="project-card">
    <div class="project-number">01</div>
    <div class="item-meta">Sep 2025 — Dec 2025</div>
    <h3>GTRM</h3>
    <p>Extended the Tiny Recursion Model with context, attention, and recurrent gating, improving Sudoku reasoning accuracy by 5.6 percentage points.</p>
    <div class="tag-row"><span>Reasoning</span><span>Tiny networks</span></div>
  </article>

  <article class="project-card">
    <div class="project-number">02</div>
    <div class="item-meta">Sep 2025 — Dec 2025</div>
    <h3>Distributionally Robust Neural Networks</h3>
    <p>Built a controlled SDXL-generated dataset and evaluated eight training regimes under spurious, style-based distribution shifts.</p>
    <div class="tag-row"><span>Robust ML</span><span>Diffusion</span></div>
  </article>

  <article class="project-card">
    <div class="project-number">03</div>
    <div class="item-meta">Feb 2024 — Jun 2024</div>
    <h3>TEULM</h3>
    <p>Developed a GPU-accelerated ultrasound localization microscopy pipeline using downsampling and 2D spatiotemporal RBF interpolation.</p>
    <div class="tag-row"><span>Medical imaging</span><span>GPU</span></div>
  </article>
</div>

<h2 id="education" class="section-heading"><span>05</span> Education & Honors</h2>

<div class="education-grid">
  <article class="education-card">
    <div class="school-badge">M</div>
    <div>
      <div class="item-meta">Aug 2025 — Expected Dec 2026</div>
      <h3>University of Michigan</h3>
      <p>M.Eng. in Electrical & Computer Engineering · GPA 4.0/4.0</p>
    </div>
  </article>
  <article class="education-card">
    <div class="school-badge school-badge--st">S</div>
    <div>
      <div class="item-meta">Sep 2021 — Jul 2025</div>
      <h3>ShanghaiTech University</h3>
      <p>B.Eng. in Computer Science · GPA 3.69/4.0 · Rank 19/180</p>
    </div>
  </article>
</div>

<div class="honors-strip">
  <span>2024</span> Merit Student, top 15%
  <span>2023</span> Outstanding Student, top 5%
</div>

<section class="contact-card" aria-labelledby="contact-title">
  <p class="eyebrow">Let’s connect</p>
  <h2 id="contact-title">Interested in agents that learn from experience?</h2>
  <p>I am always happy to talk about embodied AI, robot learning, and potential research collaborations.</p>
  <a class="home-button home-button--primary" href="mailto:wyunfei@umich.edu">wyunfei@umich.edu</a>
</section>
