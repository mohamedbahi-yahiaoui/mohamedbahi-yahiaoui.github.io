---
title: "Bounding Box Anomaly Scoring for simple and efficient Out-of-Distribution detection"
collection: publications
category: manuscripts
permalink: /publication/bbas-ood-detection
excerpt: "A post-hoc OOD detection method based on bounding-box abstraction for compact and effective representation-space support estimation."
date: 2026-03-24
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2603.22660"
citation: 'Mohamed Bahi Yahiaoui, Geoffrey Daniel, Loïc Giraldi, Jérémie Bruyelle, and Julyan Arbel. "Bounding Box Anomaly Scoring for simple and efficient Out-of-Distribution detection." arXiv:2603.22660, 2026.'
---
Out-of-distribution (OOD) detection is commonly addressed by approximating the support of in-distribution data in the representation space of a pretrained neural network. This paper introduces **Bounding Box Anomaly Scoring (BBAS)**, a post-hoc OOD detection method based on compact axis-aligned bounding-box abstractions of hidden representations. BBAS combines graded anomaly scores derived from interval exceedances, monitoring variables adapted to convolutional layers, and a decoupled clustering-and-box-construction procedure to obtain richer support estimates across layers. The resulting method preserves the simplicity, compactness, and updateability of bounding-box monitoring while providing competitive OOD detection performance on standard image-classification benchmarks.

<p align="center" style="margin-bottom: 1em;">
  <img src="/images/fig-constructing.svg" alt="BBAS methodology, panel A" width="85%">
</p>

<p align="center" style="margin-top: 0; margin-bottom: 1em;">
  <img src="/images/fig-runtime.svg" alt="BBAS methodology, panel B" width="85%">
</p>

<p align="center">
  <em><strong>Figure</strong> Overview of the BBAS methodology. Top: construction of the monitoring structure from training representations through clustering and bounding-box abstraction. Bottom: inference-time anomaly scoring based on exceedances relative to the learned support.</em>
</p>
