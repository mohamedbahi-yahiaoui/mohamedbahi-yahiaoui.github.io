---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **reliable AI**, **scientific machine learning**, and **deployable ML for high-stakes systems**. I am particularly interested in methods that make neural models trustworthy enough for real scientific workflows, especially through monitoring, uncertainty-aware reasoning, and robust deployment strategies.

## Research Themes

### Reliable AI and monitoring

I work on runtime monitoring, out-of-distribution and out-of-model-scope detection, and uncertainty-aware diagnostics for neural systems that must operate beyond ideal laboratory conditions. A recurring question in my work is how to detect when a model is leaving its operational domain and how to support safe fallback behavior. Representation-space methods appear here as a secondary thread, especially when hidden activations offer useful signals for post-hoc diagnosis.

### Neural surrogates for scientific simulation

I develop neural surrogate models for demanding multiphysics workflows, including applications in thermodiffusion and fission-gas simulation. The central challenge is not only speed, but also trustworthiness: learned surrogates must be validated carefully, monitored in operation, and integrated in ways that respect the constraints of existing scientific codes.

### Uncertainty-aware learning from physical signals

Another part of my work concerns learning from noisy detector signals, where prediction quality must be paired with meaningful uncertainty information. This includes gamma-photon interaction reconstruction in fast scintillator detectors and related problems in scientific sensing, where partial observability and measurement noise make robust estimation essential.

### Research engineering and deployment

I care about the engineering side of research as well as the modeling side. My work includes PyTorch-based experimentation, reproducible training and evaluation pipelines, deployment-aware ML, and integration into established scientific software environments. I am especially interested in settings where rigorous evaluation and practical deployment have to coexist.

## Selected Projects

<div class="project-grid">
  <section class="project-card">
    <h3>BBAS for post-hoc OOD detection</h3>
    <p><strong>Problem.</strong> Neural models can behave unpredictably under distribution shift, yet many monitoring methods are too heavy or too specialized for practical use.</p>
    <p><strong>Method.</strong> BBAS uses compact bounding-box abstractions of hidden representations, together with clustering and exceedance-based anomaly scoring, to provide a lightweight post-hoc monitoring signal.</p>
    <p><strong>Why it matters.</strong> The method is simple, updateable, and suited to deployment settings where one needs distribution-shift awareness without redesigning the underlying model.</p>
    <p><a href="/publication/bbas-ood-detection/">Related publication</a></p>
  </section>
  <section class="project-card">
    <h3>Neural surrogates for thermodiffusion and fission-gas workflows</h3>
    <p><strong>Problem.</strong> High-fidelity multiphysics simulations can be too expensive for repeated use across large parameter studies or long time horizons.</p>
    <p><strong>Method.</strong> I developed neural surrogate models for OpenCalphad and CARACAS/ALCYONE workflows, together with monitoring, trajectory-aware design, and fallback logic for safe integration.</p>
    <p><strong>Why it matters.</strong> Scientific ML becomes useful only when acceleration is paired with scientifically grounded validation and deployment strategies.</p>
    <p><a href="/publication/modele-reseau-neurones-thermodiffusion/">Related publication</a> and <a href="/publication/reliable-neural-network-thermodiffusion-icapp/">conference paper</a></p>
  </section>
  <section class="project-card">
    <h3>Uncertainty-aware reconstruction in fast scintillator detectors</h3>
    <p><strong>Problem.</strong> Detector-signal reconstruction must cope with noise, ambiguity, and incomplete observability while still producing useful estimates of interaction location and timing.</p>
    <p><strong>Method.</strong> I worked on deep-learning approaches that infer gamma-photon interaction parameters together with predictive uncertainty from detector signals.</p>
    <p><strong>Why it matters.</strong> Reliable uncertainty estimates make learned reconstruction methods more informative for scientific imaging and sensing pipelines.</p>
    <p><a href="/publication/deep-learning-scintillator-detectors/">Related publication</a></p>
  </section>
</div>

## Current Interests

- Reliable AI for high-stakes scientific systems
- Scientific ML and hybrid modeling
- OOD/OMS detection and uncertainty-aware deployment
- Efficient and deployable deep learning

## Opportunities and Collaboration

I am open to postdoctoral and research engineer opportunities, as well as collaborations in reliable AI, scientific ML, uncertainty-aware ML, and deployable ML systems for scientific applications.
