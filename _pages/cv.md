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

Researcher and machine-learning engineer with experience in **reliable AI**, **scientific ML**, **representation learning**, and **uncertainty quantification**. My recent work combines methodological research with implementation in applied scientific settings at CEA, with contributions spanning **out-of-distribution detection**, **representation-space monitoring**, **uncertainty-aware reconstruction**, and **scientific ML for multiphysics simulation**.

I am currently seeking **postdoctoral** and **research engineer** opportunities where I can contribute to reliable AI, scientific ML, representation learning, scientific software, and deployable ML systems for high-stakes environments. While my recent applications have been in nuclear simulation and detector imaging, the methods I work on are broadly transferable to other research and industrial domains.

## Experience

### CEA Cadarache - Research Engineer
**November 2022 - November 2025**

- Developed **BBAS**, a runtime monitoring method for neural surrogates under distribution shift.
- Studied out-of-distribution and out-of-model-scope detection through bounding-box abstraction, activation patterns, clustering, and multi-layer monitoring of hidden representations.
- Evaluated the monitoring approach on standard OOD benchmarks and extended it to convolutional and transformer architectures.
- Built and evaluated surrogate models for **OpenCalphad** and **CARACAS/ALCYONE** workflows, including data generation, preprocessing, training, monitoring, and deployment.
- Designed deployment strategies with fallback to high-fidelity simulation when inputs leave the operational domain.
- Designed trajectory-aware surrogate architectures for long-horizon multiphysics simulation.
- Developed reusable research code and experimentation pipelines for integrating learned surrogates into existing scientific software workflows.

### CEA Saclay - Research Engineer, AAIMME Project
**February 2022 - September 2022**

- Worked on inverse reconstruction for PET imaging, estimating gamma-photon interaction position and time from complex detector signals.
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

Coursework: applied analysis, stochastic modeling and statistical learning, optimization and machine learning, scientific computing, numerical simulation, and metamodeling/global optimization.

### Institut National des Postes et Telecommunications, Rabat
**Engineering degree (MEng) in Data Science**

Coursework: data modeling and statistics, machine learning, software engineering, databases, systems and networks, project management, and communication.

## Skills

### Core Research Expertise

- Reliable machine learning
- Scientific machine learning
- Representation learning
- Runtime monitoring and verification of neural networks
- Out-of-distribution and out-of-model-scope detection
- Physics-informed machine learning
- Theoretical aspects of deep learning

### Technical Competencies

- Software engineering for machine learning research
- End-to-end ML pipelines for simulation workflows
- Model design, training, validation, and empirical evaluation
- Numerical analysis, scientific computing, and simulation
- Statistical modeling and uncertainty quantification

### Additional Familiarity

- Operator-learning methods
- Bayesian neural networks

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
  ICAPP 2025. Focused on dependable scientific ML for multiphysics simulation workflows.

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
