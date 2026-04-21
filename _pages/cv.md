---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download">
  <a class="btn btn--primary" href="/files/cv-bahi.pdf">Download one-page CV (PDF)</a>
</div>

## Profile

I am a PhD in Computer Science with experience in **reliable AI**, **scientific ML**, **uncertainty-aware modeling**, and **deployable deep learning for high-stakes scientific systems**. My work spans **OOD/OMS detection**, **runtime monitoring**, **neural surrogate models for multiphysics simulation**, and **uncertainty-aware learning from detector signals**.

I am currently seeking **postdoctoral** and **research engineer** opportunities where I can contribute to reliable AI, scientific ML, uncertainty-aware ML, and deployable systems for demanding research environments. Representation-space diagnostics are part of this work, but they are a secondary methodological thread within the broader goal of making neural models safer and more useful in practice.

## Experience

### CEA Cadarache - Research Engineer
**November 2022 - November 2025**

- Developed **BBAS**, a post-hoc monitoring method for OOD and OMS detection based on compact hidden-representation support estimation.
- Studied runtime monitoring under distribution shift through bounding-box abstraction, clustering, anomaly scoring, and multi-layer diagnostics on hidden representations.
- Evaluated the monitoring approach on standard OOD benchmarks and extended it to convolutional and transformer architectures.
- Built neural surrogate models for **OpenCalphad** and **CARACAS/ALCYONE** workflows, covering data generation, preprocessing, training, validation, and empirical evaluation for multiphysics simulations.
- Designed deployment and fallback logic so surrogate models can defer to reference simulations outside their operational domain.
- Developed trajectory-aware surrogate models for long-horizon fission-gas simulation workflows and contributed to a reported **100x acceleration** relative to reference simulations.
- Built reproducible PyTorch-based experimentation pipelines for integrating learned surrogates into existing scientific software environments.

### CEA Saclay - Research Engineer, AAIMME Project
**February 2022 - September 2022**

- Worked on uncertainty-aware reconstruction of gamma-photon interaction position and time from fast scintillator detector signals.
- Developed deep-learning models that coupled point prediction with predictive uncertainty for more reliable detector reconstruction.
- Contributed to work published in *Engineering Applications of Artificial Intelligence* (2024).

### CEA Saclay - Intern
**April 2021 - September 2021**

- Developed multitask deep-learning models for radioactive source identification and intensity estimation under uncertainty.
- Evaluated Density Neural Networks, Bayesian Neural Networks, and information-theoretic uncertainty measures for robust prediction.

## Education

### Universite Grenoble Alpes
**PhD in Computer Science**  
Defense: **27 November 2025**

Thesis: *Surrogate Neural Network Models with a Novel Monitoring Approach to Accelerate Multi-Physics Simulations*

### Ecole des Mines de Saint-Etienne
**MSc in Applied Mathematics**

Coursework: applied analysis, stochastic modeling and statistical learning, optimization and machine learning, scientific computing, numerical simulation, and metamodeling/global optimization.

### Institut National des Postes et Telecommunications, Rabat
**Engineering degree (MEng) in Data Science**

Coursework: data modeling and statistics, machine learning, software engineering, databases, systems and networks, project management, and communication.

## Skills

### Research Areas

- Reliable AI and uncertainty quantification
- Scientific ML for simulation and neural surrogates
- Runtime monitoring, OOD/OMS detection, and representation-space diagnostics
- Uncertainty-aware learning from physical signals
- Physics-informed and deployable ML for high-stakes systems

### Technical Skills

- PyTorch and deep learning experimentation
- Reproducible training, validation, and evaluation workflows
- End-to-end ML pipelines for simulation environments
- Numerical analysis, scientific computing, and statistical modeling
- Integration and deployment logic for scientific software workflows
- Operator-learning methods and Bayesian neural networks

### Languages

- French (bilingual)
- English (bilingual)
- Arabic (native)

## Selected Work

- **Bounding Box Anomaly Scoring for simple and efficient Out-of-Distribution detection**  
  arXiv preprint, 2026. Introduces a compact and updateable post-hoc OOD detection method based on hidden-representation support estimation.

- **Deep Learning reconstruction with uncertainty estimation for gamma photon interaction in fast scintillator detectors**  
  Engineering Applications of Artificial Intelligence, 2024. Combines detector-signal reconstruction with uncertainty estimation for more reliable predictions.

- **Reliable Neural Network Model for Accelerating Coupled Thermodiffusion Simulations**  
  ICAPP 2025. Focused on reliable neural surrogates for multiphysics simulation workflows.

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
