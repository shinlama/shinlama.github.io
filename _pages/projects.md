---
layout: page
title: research
permalink: /research/
description: Selected research and prototypes.
nav: true
nav_order: 2
---

<div class="research-list">
  <article class="research-entry" id="indoor-3d">
    <div class="research-copy">
      <p class="entry-meta">2026 · 3D Vision</p>
      <h2>Indoor Reconstruction with 3D Gaussian Splatting</h2>
      <p>Compared sparse-view 3D reconstruction methods using seven to eight indoor images, with InstantSplat as a baseline. Built a Gradio interface for generating and inspecting reconstructed scenes.</p>
      <p class="entry-tools">3D Gaussian Splatting · InstantSplat · PyTorch · Gradio</p>
    </div>
    <figure>
      <img src="/assets/img/projects/3dgs-indoor-reconstruction.png" alt="Input room images, reconstructed indoor scene, and web interface" loading="eager">
    </figure>
  </article>

  <article class="research-entry" id="placeness">
    <div class="research-copy">
      <p class="entry-meta">2026 · Spatial Data Analysis</p>
      <h2>Quantifying Place Experience from Spatial Reviews</h2>
      <p>Developed an LLM-assisted pipeline that maps qualitative place reviews to ten spatial factors and produces interpretable scores. The work received a Best Presentation Award at the Korean Institute of Interior Design Conference.</p>
      <p class="entry-tools">LLM-based text analysis · Evaluation framework · Streamlit</p>
    </div>
    <figure>
      <img src="/assets/img/projects/placeness-analysis.png" alt="Web interface mapping spatial review sentences to place factors" loading="lazy">
    </figure>
  </article>

  <article class="research-entry" id="architect-generation">
    <div class="research-copy">
      <p class="entry-meta">2024 · Generative AI</p>
      <h2>Architect-Specific Building Image Generation</h2>
      <p>Fine-tuned Stable Diffusion 1.5 and evaluated how reinforced data processing changes the generation of architect-specific visual characteristics. Contributed experiments and analysis to an IEEE MIT URTC paper.</p>
      <p class="entry-tools">Stable Diffusion · Fine-tuning · Image evaluation</p>
      <p class="entry-links"><a href="https://doi.org/10.1109/URTC65039.2024.10937567">Paper <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i></a></p>
    </div>
    <figure>
      <img src="/assets/img/projects/architect-generation.png" alt="Comparison of generated building images across architects and data processing stages" loading="lazy">
    </figure>
  </article>
</div>
