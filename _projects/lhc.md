---
layout: page
title: Quark Gluon Classification using Contrastive Learning Representations
description: Self-supervised transformer to generate embeddings for particle jets and then classify them using non-linear models.
img: assets/img/mrgcn0.jpg
importance: 2
category: work
related_publications: true
---

**Supervisor**: [Dr. Tilman Plehn](https://scholar.google.com/citations?user=r3zfvh0AAAAJ&hl=en)

<!-- ---
name: 
tools: [Scikit, XGBoost, Pytorch]
image: /assets/img/lhc.jpg
description: I trained a transformer-encoder network with contrastive loss to map particle jets to a representation space. I implemented ML models to classify the obtained representations of jets into quarks and gluons.
---
# Quark Gluon Classification using Contrastive Learning Representations
##### Supervisor: <a href = "https://www.thphys.uni-heidelberg.de/~plehn/"> Dr. Tilman Plehn </a>

<br> -->
Our building blocks are atomic nuclei, which in turn comprise protons and neutrons, which are made up of quarks and gluons. This project aims to distinguish the quarks (signal) from the gluons (background).

{% include figure.liquid loading="eager" path="assets/img/lhc.jpg" title="Large Hadron Collider" %}

When a collision takes place in the Large Hadron Collider, constituent particles get scattered. The set of scattered particles are called jets. Snapshots of jets are called jet images and have been conventionally used to classify between quark and gluon initiated jets.
In this research work, we adopt an alternative technique. We train a transformer with contrastive loss to map particle jets to a representation space. Spherical position, particle type and transverse momentum  of the constituent particles are taken into consideration while obtaining the representation of jets.

These linear representations are fed into machine learning models for binary classification tasks (to distinguish between quarks and gluons.)

### Technical Details

* Semi-Supervised Learning
* BERT for Language Modeling
* **Framework**: Pytorch
* **Model**:  Logistic Regression, Linear Discriminant Analysis, Random Forest, XGBoost

### Results
We've obtained an AUC of 0.8 so far. Research work is still ongoing.


[View Code](https://github.com/nikita-0209/ml_quark_gluon)
