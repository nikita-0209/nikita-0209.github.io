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

The XENON experiment, located in Italy, utilizes a cylindrical detector filled with liquid Xenon and equipped with hexagonally arranged vacuum tubes to search for potential dark matter candidates by detecting photons from particle interactions. The hexagonal arrangement of photon sensors within the detector naturally lends itself to a graph-based representation, motivating the exploration of GNNs for this task. The goal of this project was to develop a model capable of accurately determining the spatial coordinates of particle interactions within the liquid Xenon medium given the energy (ADC) recorded in each vacuum tube.

{% include figure.liquid loading="eager" path="assets/img/ucsd.jpg" title="The XENON Detector" class="img-fluid rounded z-depth-1" %}

A GNN model was designed and implemented using the Spektral library, built upon the Keras and Tensorflow frameworks.

The resulting GNN model, trained by self-supervised techniques, comprised approximately 200,000 trainable parameters, demonstrated significant performance improvements in position reconstruction accuracy. It achieved a Root Mean Squared Error (RMSE) of 1.936 cm. Notably, this performance represents a 12% improvement over a benchmark Convolutional Neural Network (CNN) with significantly more parameters (5 million) and a substantial 67% improvement compared to the established position reconstruction software currently utilized by the XENON experiment, known as straxen. These results highlight the efficacy of GNNs in leveraging the specific geometric structure of the XENON detector for enhanced position reconstruction capabilities.

<!-- [View Presentation](https://docs.google.com/presentation/d/1GxSzdwGt5Zl98TtHSi_1zIr8pTvJ7l0HLCpeG3pLFU4/present?slide=id.g35f391192_00) -->
