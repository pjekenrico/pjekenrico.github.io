---
layout: default
title: Home
---

<nav class="page-nav">
  <a href="#about">About</a>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
</nav>

<header class="hero">
  <h1>Pablo Jeken Rico</h1>
  <p class="hero-tagline">Computational Mathematician &middot; Research Scientist &middot; HPC &amp; Medical Imaging</p>
  <div class="hero-links">
    <a href="mailto:pablojeken@hotmail.com">&#9993; pablojeken@hotmail.com</a>
    <a href="https://github.com/pjekenrico" target="_blank">&#9670; GitHub</a>
    <span>&#128205; Paris, France</span>
  </div>
</header>

---

<section id="about">

## About

Computational mathematician and researcher specialising in high-performance computing, scientific computing, and medical applications. Currently a Research Scientist at Philips, implementing and optimising GPU-based image-enhancement algorithms for clinical ultrasound (2D &amp; 3D texture processing). Previously worked on PhD and PostDoc research at Cemef, Mines Paris &ndash; PSL University, focusing on hemodynamics modelling and machine-learning approaches for intracranial aneurysm risk assessment.

</section>

---

<section id="career">

## Experience &amp; Education

<div class="timeline" id="experience">

  <article class="timeline-event timeline-event--left">
    <span class="timeline-event__track">Experience</span>
    <time>2025 &ndash; Present</time>
    <h3>Research Scientist &ndash; Philips Healthcare</h3>
    <p>Clinical ultrasound image quality. Implementation and optimisation of shape-adaptive GPU filters for real-time 2D/3D ultrasound texture processing on-cart (NVIDIA RTX GPU).</p>
  </article>

  <article class="timeline-event timeline-event--right">
    <span class="timeline-event__track">Experience</span>
    <time>2024 &ndash; 2025</time>
    <h3>PostDoc &ndash; Cemef, Mines Paris &middot; PSL University</h3>
    <p>Machine-learning approaches for intracranial aneurysm risk assessment.</p>
  </article>

  <article class="timeline-event timeline-event--left">
    <span class="timeline-event__track">Experience</span>
    <time>2021 &ndash; 2024</time>
    <h3>PhD Researcher &ndash; Cemef, Mines Paris &middot; PSL University</h3>
    <p>Thesis: <em>Hemodynamic Modelling and Simulation of Flow Diverters for Intracranial Aneurysm Treatment</em>. Derived and implemented a wiring algorithm for braided flow-diverter stents; published in <em>Computers in Biology and Medicine</em>.</p>
  </article>

  <article class="timeline-event timeline-event--right" id="education">
    <span class="timeline-event__track">Education</span>
    <time>2020 &ndash; 2021</time>
    <h3>M.Sc. Applied Mathematics &ndash; KTH Royal Institute of Technology, Stockholm</h3>
  </article>

  <article class="timeline-event timeline-event--left">
    <span class="timeline-event__track">Education</span>
    <time>2019 &ndash; 2020</time>
    <h3>M.Sc. Applied Mathematics &ndash; TU Delft <span class="badge">Cum Laude</span></h3>
  </article>

  <article class="timeline-event timeline-event--right">
    <span class="timeline-event__track">Education</span>
    <time>2015 &ndash; 2019</time>
    <h3>B.Sc. Physics Engineering &ndash; TU Berlin</h3>
  </article>

  <article class="timeline-event timeline-event--left">
    <span class="timeline-event__track">Education</span>
    <time>2003 &ndash; 2015</time>
    <h3>Deutsche Schule Madrid</h3>
  </article>

</div>

</section>

---

<section id="skills">

## Skills

<div class="skills-grid">

  <div class="skills-group">
    <h3>Programming</h3>
    <div class="skill-tags">
      <span class="skill-tag">C++</span>
      <span class="skill-tag">Python</span>
      <span class="skill-tag">CUDA</span>
      <span class="skill-tag">C#</span>
      <span class="skill-tag">VTK</span>
    </div>
  </div>

  <div class="skills-group">
    <h3>Tools &amp; DevOps</h3>
    <div class="skill-tags">
      <span class="skill-tag">Git / GitLab / SVN</span>
      <span class="skill-tag">CI/CD</span>
      <span class="skill-tag">HPC</span>
      <span class="skill-tag">SSH / SCP</span>
      <span class="skill-tag">GPU Computing</span>
    </div>
  </div>

  <div class="skills-group">
    <h3>Research Areas</h3>
    <div class="skill-tags">
      <span class="skill-tag">Scientific Computing</span>
      <span class="skill-tag">Fluid-Structure Interaction</span>
      <span class="skill-tag">Hemodynamics</span>
      <span class="skill-tag">Medical Imaging</span>
      <span class="skill-tag">Machine Learning</span>
    </div>
  </div>

  <div class="skills-group">
    <h3>Languages</h3>
    <div class="skill-tags">
      <span class="skill-tag">German C2</span>
      <span class="skill-tag">Spanish C2</span>
      <span class="skill-tag">English C1/C2</span>
      <span class="skill-tag">French (Fluent)</span>
    </div>
  </div>

</div>

</section>

---

<section id="projects">

## Projects &amp; Publications

<div class="project-cards">

  <div class="project-card">
    <h3>Shape-Adaptive Filtering for Ultrasound</h3>
    <p>Development of robust filters for real-time ultrasound image treatment. Implementation and optimisation of on-cart NVIDIA RTX GPU routines at Philips.</p>
    <div class="project-links">
      <a href="https://www.usa.philips.com/healthcare/article/ultrasound-innovation-nvidia-rtx-gpu-beamforming" target="_blank">Philips article &rarr;</a>
    </div>
  </div>

  <div class="project-card">
    <h3>Virtual Flow Diverter Deployment for Hemodynamic Simulations</h3>
    <span class="pub-venue">Computers in Biology and Medicine &middot; 2024</span>
    <img class="project-image" src="{{ '/assets/images/stent_paper_img.png' | relative_url }}" alt="Virtual flow diverter deployment visual from the 2024 publication.">
    <p>Derivation and implementation of a wiring algorithm for braided flow-diverter stents enabling virtual deployment and hemodynamic simulation.</p>
    <div class="project-links">
      <a href="https://www.sciencedirect.com/science/article/pii/S0010482524011089" target="_blank">Paper &rarr;</a>
      <a href="https://github.com/pjekenrico/py_geo_fd" target="_blank">Code &rarr;</a>
    </div>
  </div>

  <div class="project-card">
    <h3>Impact of Domain Boundaries on Hemodynamics in Intracranial Aneurysms</h3>
    <span class="pub-venue">Fluids (MDPI) &middot; 2024</span>
    <img class="project-image" src="{{ '/assets/images/evaluation_paper.png' | relative_url }}" alt="Domain boundary evaluation figure from the 2024 Fluids publication.">
    <p>Evaluating how inlet/outlet boundary placement within the Circle of Willis affects hemodynamic predictions in intracranial aneurysm simulations.</p>
    <div class="project-links">
      <a href="https://www.mdpi.com/2311-5521/9/1/1" target="_blank">Paper &rarr;</a>
    </div>
  </div>

  <div class="project-card">
    <h3>Delayed Rupture of Flow Diverter-Treated Giant Aneurysm</h3>
    <span class="pub-venue">Bioengineering (MDPI) &middot; 2025</span>
    <img class="project-image" src="{{ '/assets/images/rupture_paper.png' | relative_url }}" alt="Simulation figure for delayed rupture risk after flow diverter treatment.">
    <p>Investigating delayed rupture risk after flow diverter treatment of a giant aneurysm using fluid&ndash;structure interaction simulations.</p>
    <div class="project-links">
      <a href="https://www.mdpi.com/2306-5354/12/3/305" target="_blank">Paper &rarr;</a>
    </div>
  </div>

  <div class="project-card project-card--wide">
    <h3>FDA Nozzle &mdash; Transitional Flow Simulation</h3>
    <p>Computational fluid dynamics simulation of transitional flow through the FDA benchmark nozzle geometry. Visualisation of 600 time frames capturing the laminar-to-turbulent transition regime.</p>
    <video class="project-video" autoplay loop muted playsinline>
      <source src="{{ '/assets/videos/fda_nozzle.mp4' | relative_url }}" type="video/mp4">
      <source src="{{ '/assets/videos/fda_nozzle.webm' | relative_url }}" type="video/webm">
      Your browser does not support the video tag.
    </video>
  </div>

</div>

</section>
