---
layout: page
title: Contrastive Learning for Quark-Gluon Jet Classification.
description: Self-supervised transformer to generate embeddings for particle jets and then classify them using non-linear models.
img: assets/img/lhc.jpg
importance: 2
category: work
related_publications: false
---

**Supervisor**: [Dr. Tilman Plehn](https://scholar.google.com/citations?user=r3zfvh0AAAAJ&hl=en), [Dr. Barry Dillion](https://scholar.google.com/citations?user=HeQ0Xs0AAAAJ&hl=en)

<!-- ---
name: 
tools: [Scikit, XGBoost, Pytorch]
image: /assets/img/lhc.jpg
description: I trained a transformer-encoder network with contrastive loss to map particle jets to a representation space. I implemented ML models to classify the obtained representations of jets into quarks and gluons.
---
# Quark Gluon Classification using Contrastive Learning Representations
##### Supervisor: <a href = "https://www.thphys.uni-heidelberg.de/~plehn/"> Dr. Tilman Plehn </a>

<br> -->
We adopt the JetCLR framework, a self-supervised contrastive learning approach, to the task of quark-gluon jet tagging. Initially tested on top-tagging, JetCLR is here applied to a quark-gluon dataset that includes particle-ID (PID) information alongside standard kinematic data $$(pT, η, φ)$$. The primary goal is to evaluate the performance of JetCLR-generated representations for linear quark/gluon discrimination. This involves comparing these representations against established alternatives, specifically Energy Flow Polynomials (EFPs), using various linear classifier tests (LCTs). The study investigates different JetCLR configurations, including variations with and without PID information, and explores different methods for encoding PIDs, such as single float values (PFN-ID, PFN-Ex, JetCLR-ID) and one-hot encoding.

{% include figure.liquid loading="eager" path="assets/img/lhc.jpg" title="Large Hadron Collider" class="img-fluid rounded z-depth-1" %}

Initial results indicate that JetCLR representations, particularly when incorporating one-hot encoded PIDs show promising performance, achieving comparable or slightly better results than standard EFPs depending on the linear classfier used (e.g., outperforming EFPs with BCE loss but underperforming with Linear Discriminant Analysis). The quark-gluon dataset was generated using Pythia 8.226 for pp collisions at 14 TeV, focusing on Z+jet events within a pT range of 500-550 GeV. Further investigations include optimizing hyperparameters like the contrastive loss temperature and assessing the impact of different data augmentations and potential detector effects on the classification performance.

[View Code](https://github.com/nikita-0209/ml_quark_gluon)
[Report](https://github.com/nikita-0209/ml_quark_gluon)
