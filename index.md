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
  <div class="hero-content">
    <div class="hero-text">
      <h1>Pablo Jeken Rico</h1>
      <p class="hero-tagline">Computational Mathematician &middot; Research Scientist &middot; HPC &amp; Medical Imaging</p>
      <div class="hero-links">
        <a href="mailto:pablojeken@hotmail.com">&#9993; pablojeken@hotmail.com</a>
        <a href="https://github.com/pjekenrico" target="_blank">&#9670; GitHub</a>
        <span>&#128205; Paris, France</span>
      </div>
    </div>
    <img class="hero-photo" src="{{ '/assets/images/pablo.jpg' | relative_url }}" alt="Portrait of Pablo Jeken Rico.">
  </div>
</header>

---

<section id="about">

<h2 class="section-title">About</h2>

Computational mathematician and researcher specialising in high-performance computing, scientific computing, and medical applications. Currently a Research Scientist at Philips, implementing and optimising GPU-based image-enhancement algorithms for clinical ultrasound. Previously worked on PhD and PostDoc research at Cemef, Mines Paris &ndash; PSL University, focusing on hemodynamics modelling and machine-learning approaches for intracranial aneurysm risk assessment.

</section>

---

<section id="career">

<h2 class="section-title">Experience &amp; Education</h2>

<div class="map-timeline" style="background-image: url('{{ '/assets/logos/Europe_edit-eps-converted-to.pdf' | relative_url }}');">
  <svg viewBox="0 0 1000 600" class="map-timeline-svg" preserveAspectRatio="xMidYMid slice">
    <!-- Connecting lines with bezier curves -->
    <g class="timeline-connectors">
      <!-- School (Spain) - cyan -->
      <path d="M 120 580 Q 300 450 420 380" stroke="#06b6d4" stroke-width="3" fill="none"/>
      <!-- Bachelor (Berlin) - green -->
      <path d="M 220 520 Q 380 400 480 320" stroke="#22c55e" stroke-width="3" fill="none"/>
      <!-- Practical Exp (Germany) - gold -->
      <path d="M 320 480 Q 450 380 520 300" stroke="#f59e0b" stroke-width="3" fill="none"/>
      <!-- Masters (KTH) - red -->
      <path d="M 180 400 Q 380 300 540 240" stroke="#ef4444" stroke-width="3" fill="none"/>
      <!-- Masters (Delft) - red -->
      <path d="M 200 380 Q 400 280 520 220" stroke="#ef4444" stroke-width="3" fill="none"/>
      <!-- PhD (Paris) - orange -->
      <path d="M 380 350 Q 520 250 600 180" stroke="#f97316" stroke-width="3" fill="none"/>
    </g>
    
    <!-- Location circles -->
    <g class="timeline-markers">
      <circle cx="420" cy="380" r="8" fill="none" stroke="#06b6d4" stroke-width="2"/>
      <circle cx="480" cy="320" r="8" fill="none" stroke="#22c55e" stroke-width="2"/>
      <circle cx="520" cy="300" r="8" fill="none" stroke="#f59e0b" stroke-width="2"/>
      <circle cx="540" cy="240" r="8" fill="none" stroke="#ef4444" stroke-width="2"/>
      <circle cx="520" cy="220" r="8" fill="none" stroke="#ef4444" stroke-width="2"/>
      <circle cx="600" cy="180" r="8" fill="none" stroke="#f97316" stroke-width="2"/>
    </g>
  </svg>
  
  <!-- Timeline boxes positioned over the map -->
  <div class="timeline-boxes">
    <div class="timeline-box timeline-box--school" style="--color: #06b6d4;">
      <h3>School</h3>
      <ul>
        <li>Deutsche Schule Madrid</li>
        <li>Deutsche Schule Barcelona</li>
      </ul>
      <span class="timeline-year">2003 &ndash; 2015</span>
    </div>
    
    <div class="timeline-box timeline-box--bachelor" style="--color: #22c55e;">
      <h3>Bachelor</h3>
      <p>Physics Engineering</p>
      <p>TU Berlin</p>
      <span class="timeline-year">2015 &ndash; 2019</span>
    </div>
    
    <div class="timeline-box timeline-box--practical" style="--color: #f59e0b;">
      <h3>Practical Exp.</h3>
      <div class="logo-row">
        <img src="{{ '/assets/logos/basf.png' | relative_url }}" alt="BASF" class="logo-mini">
        <img src="{{ '/assets/logos/voith.png' | relative_url }}" alt="Voith" class="logo-mini">
        <img src="{{ '/assets/logos/enercon.png' | relative_url }}" alt="Enercon" class="logo-mini">
      </div>
    </div>
    
    <div class="timeline-box timeline-box--masters-kth" style="--color: #ef4444;">
      <h3>Master</h3>
      <p>Applied Mathematics</p>
      <p>KTH Stockholm</p>
      <span class="timeline-year">2020 &ndash; 2021</span>
    </div>
    
    <div class="timeline-box timeline-box--masters-delft" style="--color: #ef4444;">
      <h3>Master</h3>
      <p>Applied Mathematics</p>
      <p>TU Delft</p>
      <span class="timeline-year">2019 &ndash; 2020</span>
      <span class="badge">Cum Laude</span>
    </div>
    
    <div class="timeline-box timeline-box--phd" style="--color: #f97316;">
      <h3>PhD &amp; PostDoc</h3>
      <p>Computational Mathematics, HPC &amp; Data</p>
      <p>Cemef, Mines Paris &ndash; PSL</p>
      <span class="timeline-year">2021 &ndash; 2025</span>
    </div>
  </div>
</div>

</section>

---

<section id="skills">

<h2 class="section-title">Skills</h2>

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

<h2 class="section-title">Projects &amp; Publications</h2>

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
    <p>Evaluating how inlet/outlet boundary placement within the Circle of Willis affects hemodynamic predictions in intracranial aneurysm simulations.</p>
    <div class="project-links">
      <a href="https://www.mdpi.com/2311-5521/9/1/1" target="_blank">Paper &rarr;</a>
    </div>
    <video class="project-video" autoplay loop muted playsinline>
      <source src="{{ '/assets/videos/CoW.mp4' | relative_url }}" type="video/mp4">
      <source src="{{ '/assets/videos/CoW.webm' | relative_url }}" type="video/webm">
      Your browser does not support the video tag.
    </video>
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

  <div class="project-card">
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
