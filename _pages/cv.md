---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF version](/files/cv-bahi.pdf)

## Profile

Researcher and machine-learning engineer with experience in **scientific machine learning**, **reliable AI**, **uncertainty quantification**, and **physics-based surrogate modeling**. My recent work combines methodological research with implementation in applied scientific settings at CEA, with contributions spanning **out-of-distribution detection**, **uncertainty-aware reconstruction**, and **neural surrogates for multiphysics simulations**.

I am currently seeking **postdoctoral** and **research engineer** opportunities where I can contribute to trustworthy ML, AI for science, robust computer vision, scientific software, and deployable ML systems for high-stakes environments. While my recent applications have been in nuclear simulation and detector imaging, the methods I work on are broadly transferable to other research and industrial domains.

<div class="career-grid">
  <section class="career-card">
    <h3>Best Fit For</h3>
    <ul>
      <li>Postdoc in scientific ML, trustworthy AI, uncertainty quantification, or AI for physics</li>
      <li>Research engineer roles in applied ML, simulation acceleration, imaging, or robust model evaluation</li>
    </ul>
  </section>
  <section class="career-card">
    <h3>Key Strengths</h3>
    <ul>
      <li>Bridges theory, experiments, and implementation</li>
      <li>Strong experience with safety-aware and uncertainty-aware ML</li>
      <li>Comfortable in multidisciplinary scientific environments</li>
    </ul>
  </section>
  <section class="career-card">
    <h3>Selected Evidence</h3>
    <ul>
      <li>100x acceleration for thermodiffusion simulation surrogates</li>
      <li>Recent arXiv preprint on competitive OOD detection</li>
      <li>Published in EAAI and presented at ICAPP and JdS</li>
    </ul>
  </section>
</div>

## Experience

### CEA Cadarache - Research Engineer
**November 2022 - November 2025**

- Developed a post-hoc out-of-distribution detection method with competitive benchmark performance, centered on compact support estimation in representation spaces.
- Built dynamic neural-network surrogate models for transport and accumulation of fission gases over the full reactor lifetime, accelerating reference simulations by about **100x**.
- Designed monitoring-oriented surrogate approaches for multiphysics workflows where reliability and computational efficiency are both critical.
- Developed neural-network surrogate models for a Gibbs energy minimizer in scientific computing settings.

### CEA Saclay - Research Engineer, AAIMME Project
**February 2022 - September 2022**

- Worked on inverse reconstruction with deep learning for PET imaging, estimating gamma-photon interaction position and time from complex detector signals.
- Developed uncertainty-aware approaches combining point predictions with uncertainty estimates for interaction parameters.
- Contributed to methods that improved trustworthiness for scientific imaging pipelines and detector signal interpretation.

### CEA Saclay - Intern
**April 2021 - September 2021**

- Developed a multitask deep-learning model for identification and intensity estimation of radioactive sources with explicit uncertainty quantification.
- Evaluated Density Neural Networks, Bayesian Neural Networks, and information-theoretic uncertainty measures for robust prediction.

## Education

### Universite Grenoble Alpes
**PhD in Computer Science**  
Defense: **27 November 2025**

Thesis: *Surrogate Neural Network Models with a Novel Monitoring Approach to Accelerate Multi-Physics Simulations*

### Ecole des Mines de Saint-Etienne
**MSc in Applied Mathematics**

Coursework included stochastic modeling, statistical learning, and numerical modeling.

### Institut National des Postes et Telecommunications, Rabat
**Engineering degree (MEng) in Data Science**

Coursework included machine learning, statistical modeling, software engineering, big data, and distributed systems.

## Research Themes

- **Reliable AI:** Out-of-distribution detection, uncertainty quantification, calibration, robustness evaluation
- **Scientific machine learning:** Neural surrogate modeling, multiphysics acceleration, monitoring, deployment-aware design
- **Computer vision and inverse problems:** Reconstruction from detector signals, uncertainty-aware estimation
- **Applied ML systems:** Reproducible experimentation, evaluation workflows, deployment-aware model development

## Skills

- **Scientific machine learning:** Physics-informed neural networks (PINNs), neural surrogate modeling, operator learning
- **Core ML:** Deep learning, representation learning, computer vision, multi-task learning
- **Reliable AI:** Uncertainty quantification, out-of-distribution detection, calibration, robustness evaluation
- **Modeling and computation:** Inverse problems, numerical modeling, optimization, statistical learning
- **Software and engineering:** Python, C++, Linux, Git, reproducible experimentation, profiling, deployment
- **Languages:** French (bilingual), English (bilingual), Arabic (native)

## Selected Outputs

- **Bounding Box Anomaly Scoring for simple and efficient Out-of-Distribution detection**  
  arXiv preprint, 2026. Introduces a compact and updateable post-hoc OOD detection method based on hidden-representation support estimation.

- **Deep Learning reconstruction with uncertainty estimation for gamma photon interaction in fast scintillator detectors**  
  Engineering Applications of Artificial Intelligence, 2024. Combines detector-signal reconstruction with uncertainty estimation for more reliable predictions.

- **Reliable Neural Network Model for Accelerating Coupled Thermodiffusion Simulations**  
  ICAPP 2025. Focused on dependable neural surrogates for multiphysics simulation acceleration.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
