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


## Experience

### CEA Cadarache — Research Engineer
**November 2022 – November 2025**

- Developed an out-of-distribution detection method reaching state-of-the-art performance.
- Built dynamic neural-network surrogate models for transport and accumulation of fission gases over the full reactor lifetime, accelerating reference simulations by a factor of 100.
- Developed neural-network surrogate models for a Gibbs energy minimizer.

### CEA Saclay — Research Engineer, AAIMME Project
**February 2022 – September 2022**

- Worked on inverse reconstruction with deep learning for PET imaging: estimation of gamma-photon interaction position and time from complex detector signals.
- Developed uncertainty-aware approaches, including point estimates and associated uncertainty estimates for interaction parameters.

### CEA Saclay — Intern
**April 2021 – September 2021**

- Developed a multitask deep-learning model for identification and intensity estimation of radioactive sources, with explicit uncertainty quantification.
- Studied Density Neural Networks, Bayesian Neural Networks, and information-theoretic uncertainty measures.

## Education

### Université Grenoble Alpes
**PhD in Computer Science**  
Defense: **27 November 2025**

Thesis: *“Métamodèles de réseaux de neurones avec une nouvelle approche de monitoring pour accélérer les simulations multiphysiques”*

### École des Mines de Saint-Étienne
**MSc in Applied Mathematics**

Coursework included stochastic modeling, statistical learning, and numerical modeling.

### Institut National des Postes et Télécommunications, Rabat
**Engineering degree (MEng) in Data Science**

Coursework included machine learning, statistical modeling, software engineering, big data, and distributed systems.

## Skills

- **Scientific machine learning:** Physics-informed neural networks (PINNs), neural surrogate modeling, operator learning
- **Core ML:** Deep learning, representation learning, computer vision, multi-task learning
- **Reliable AI:** Uncertainty quantification, out-of-distribution detection, calibration, robustness evaluation
- **Modeling & computation:** Inverse problems, numerical modeling, optimization, statistical learning
- **Software & engineering:** Python, C++, Linux, Git, reproducible experimentation, profiling, deployment
- **Languages:** French (bilingual), English (bilingual), Arabic (native)

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