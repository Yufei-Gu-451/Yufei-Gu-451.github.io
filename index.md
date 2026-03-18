---
layout: default
title: Home
---

<div class="landing-page">
  <section class="hero-card">
    <div class="hero-copy">
      <p class="eyebrow">PhD Student, Learning Theory, Optimization</p>
      <h1>Yufei Gu</h1>
      <p class="lead">Bridging the gap between the theoretical understandings and empirical practises in the field of deep learning.</p>
      <p>My enthusiasm lies in the computational aspects of deep learning theory and advanced methodologies for optimization and generalization. My current research interest focuses on analyzing the learning dynamics and developing efficient optimizers for pre-training and post-training LLMs.</p>

      <div class="hero-actions">
        <a class="button-primary" href="./publications">Publications</a>
        <a class="button-secondary" href="./cv">Curriculum Vitae</a>
      </div>

      <nav class="section-jump" aria-label="Quick navigation">
        <a href="#biography">Biography</a>
        <a href="#research-interests">Research Interests</a>
        <a href="#news">News</a>
        <a href="#selected-bibliography">Bibliography</a>
      </nav>
    </div>

    <aside class="hero-side">
      <h2>At a Glance</h2>
      <ul class="quick-facts">
        <li><strong>Affiliation</strong><span>The Hong Kong University of Science and Technology (Guangzhou) / DSA Thrust / XLeaf Lab</span></li>
        <li><strong>Email</strong><span><a href="mailto:yufei.gu.451@outlook.com">yufei.gu.451@outlook.com</a><br><a href="mailto:ygu167@connect.hkust-gz.edu.cn">ygu167@connect.hkust-gz.edu.cn</a></span></li>
        <li><strong>Phone</strong><span>+44 07529968601 · +86 13122366091</span></li>
        <li><strong>Profiles</strong><span><a href="https://github.com/Yufei-Gu-451">GitHub</a> · <a href="https://scholar.google.com/citations?user=Yufei+Gu">Google Scholar</a></span></li>
      </ul>
    </aside>
  </section>

  <section class="content-grid">
    <div class="content-main">
      {% comment %}
      <section id="biography" class="panel">
        <p class="section-label">Biography</p>
        <h2>About My Research</h2>
        <p>I am a researcher working on <strong>[research area]</strong>. I am currently affiliated with <strong>[department/institution]</strong>, where I study <strong>[brief description of your work]</strong>. Previously, I worked on <strong>[previous topic or training]</strong> and developed an interest in <strong>[broader theme]</strong>.</p>
        <p>My long-term goal is to understand <strong>[big-picture question]</strong> and to build methods that support <strong>[impact or application]</strong>.</p>
      </section>

      <section id="research-interests" class="panel">
        <p class="section-label">Research Interests</p>
        <h2>Current Themes</h2>
        <div class="interest-list">
          <article>
            <h3>LLM Training Efficiency</h3>
            <p>Exploring optimizer design and manifold-aware strategies such as Mano to reduce compute and improve the Pareto frontier beyond AdamW.</p>
          </article>
          <article>
            <h3>Hessian Geometry</h3>
            <p>Studying power-law Hessian structures across CNNs and LLMs to relate spectral decay to generalization and interpolation behavior.</p>
          </article>
          <article>
            <h3>Modal Alignment</h3>
            <p>Building contrastive audio-visual models like SpikeCLIP that align based on spiking representations to advance multimodal pretraining.</p>
          </article>
          <article>
            <h3>Biomedical QA & Retrieval</h3>
            <p>Designing RAG-style biomedical QA systems over PubMed to benchmark retrieval-augmented generation in clinical reasoning.</p>
          </article>
        </div>
      </section>
      {% endcomment %}

      <section id="selected-bibliography" class="panel">
        <p class="section-label">Selected Bibliography</p>
        <h2>Highlighted Work</h2>
        <ol class="bibliography-list">
          <li><strong>Yufei Gu</strong>, Co-author. “Late-to-Early Training: LET LLMs Learn Earlier, So Faster and Better.” <em>ICLR 2026</em>. Explores guiding early layers with late-trained blocks for faster convergence. <a href="https://example.com/let-paper">paper</a></li>
          <li><strong>Yufei Gu</strong>, Co-first author. “Investigating the Overlooked Hessian Structure: From CNNs to LLMs.” <em>ICML 2025</em>. Documents Hessian power-laws that predict generalization. <a href="https://example.com/hessian-paper">paper</a></li>
          <li><strong>Yufei Gu</strong>, First author. “Unraveling the Enigma of Double Descent.” <em>ICLR 2024</em>. Links interpolation strategy to generalization through feature space analysis. <a href="https://example.com/double-descent">paper</a></li>
        </ol>
        <p><a href="./publications">See the full publication list →</a></p>
      </section>
    </div>

    <div class="content-side">
      <section id="news" class="panel accent-panel">
        <p class="section-label">News</p>
        <h2>Recent Updates</h2>
        <ul class="news-list">
          <li><strong>2026-03</strong><span>Accepted [ICLR'26] paper on guiding earlier LLM layers with later-trained layers for faster convergence.</span></li>
          <li><strong>2025-12</strong><span>Co-authored [ICML'25] work revealing overlooked Hessian power laws in CNNs and LLMs.</span></li>
          <li><strong>2025-08</strong><span>Started PhD in Data Science & Analytics at HKUST(GZ) while leading Mano and spectral regularization projects.</span></li>
          <li><strong>2024-06</strong><span>Contributed to Fudan SpikeCLIP contrastive pretraining and biomedical RAG system development at UCL.</span></li>
        </ul>
      </section>
    </div>
  </section>
</div>
