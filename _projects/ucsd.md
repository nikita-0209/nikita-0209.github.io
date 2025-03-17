---
layout: page
title: Graph Neural Network for the XENON Detector
description: Reconstruct the position of collisions happening in the XENON detector, an underground experiment for studying potential dark matter candidates.
img: assets/img/xenon.jpg
importance: 3
category: work
related_publications: false
---

**Supervisor**: [Dr. Kaixuan Ni](https://scholar.google.com/citations?user=jyw99D8AAAAJ&hl=ene)

Fascinated by dark matter? Well, aren't we all? And I am thrilled that I got the opportunity to directly contribute to its research!

Located in Italy, the [XENON Experiment](https://xenonexperiment.org/) was established to study potential dark matter candidates. Broadly, it is just a cylinder full of liquid Xenon with vacuum tubes (to detect photons) aligned in a hexagonal arrangement at the top and the bottom faces.

{% include figure.liquid loading="eager" path="assets/img/ucsd.jpg" title="The XENON Detector" class="img-fluid rounded z-depth-1" %}

In fact, this hexagonal arrangement piqued the community’s interest to experiment with graph neural networks. After all, what better than graphs could capture a hexagonal shape!

I designed a graph neural network to reconstruct the position of the collision happening in the detector. And my neural network performed better than the original software used by XENON to reconstruct the position!

### Technical Details

* Semi-Supervised Learning
* **Library**: [Spektral](https://github.com/danielegrattarola/spektral)
* **Framework**: Keras and Tensorflow
* **Model**: Graph Convolutional Layer

### Results

The Graph Neural Network (with 200k trainable parameters) obtained an RMSE of 1.936 cm. It outperformed a Convolutional Neural Network (with 5 million trainable parameters) by 12%, and the original software used for positon reconstruction by XENON [straxen](https://github.com/XENONnT/straxen) by 67%.

<!-- [View Presentation](https://docs.google.com/presentation/d/1GxSzdwGt5Zl98TtHSi_1zIr8pTvJ7l0HLCpeG3pLFU4/present?slide=id.g35f391192_00) -->
