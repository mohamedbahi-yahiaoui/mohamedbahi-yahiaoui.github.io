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

## Experience

### CEA Cadarache - Research Engineer
**November 2022 - November 2025**

- Developed **BBAS**, a post-hoc out-of-distribution and out-of-model-scope monitoring method based on bounding-box abstraction and activation patterns.
- Built and evaluated surrogate models for **OpenCalphad** and **CARACAS/ALCYONE** workflows, including data generation, preprocessing, training, monitoring, and deployment.
- Designed trajectory-aware surrogate architectures for long-horizon multiphysics simulation and achieved about **100x** acceleration in thermodiffusion settings.

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

- Developed a runtime monitoring framework for neural surrogates under distribution shift, centered on **Bounding Box Anomaly Score (BBAS)**.
- Studied out-of-distribution and out-of-model-scope detection through bounding-box abstraction, activation patterns, clustering, and multi-layer monitoring.
- Evaluated the monitoring approach on standard OOD benchmarks and extended it to convolutional and transformer architectures.
- Built surrogate models for **OpenCalphad** and **CARACAS/ALCYONE**, including deployment strategies with fallback to high-fidelity simulation when inputs leave the operational domain.
- Designed trajectory-aware surrogate models to improve robustness and stability in long multiphysics simulations.

### Ecole des Mines de Saint-Etienne
**MSc in Applied Mathematics**

Coursework: applied analysis, stochastic modeling and statistical learning, optimization and machine learning, scientific computing, numerical simulation, and metamodeling/global optimization.

### Institut National des Postes et Telecommunications, Rabat
**Engineering degree (MEng) in Data Science**

Coursework: data modeling and statistics, machine learning, software engineering, databases, systems and networks, project management, and communication.

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
