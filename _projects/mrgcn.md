---
layout: page
title: Multi-Relational Graph Neural Network for Darkweb Actor Classification
description: Semi-supervised deep learning framework to detect key actors by classifying underground forum users into different groups based on their activity patterns.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

# Multi-Relational Graph Neural Network for Darkweb Actor Classification
##### Supervisor: <a href = "https://www.bits-pilani.ac.in/pilani/vintiagarwal/profile"> Dr. Vinti Agarwal</a>

<br>
Cybercriminals who interact extensively
on underground forums, often, exchange illegal commodities and indulge in discussions on unwarranted
topics. To facilitate the disruption of these highly
proficient criminals, we propose a deep learning based
multi-relational graph convolutional network approach
to analyse the underground forum and identify key
actors.

{% include figure.liquid loading="eager" path="assets/img/1.jpg" title="Overall architecture of KAD-mRGCN framework" class="img-fluid rounded z-depth-1" %}

  We demonstrate the effectiveness of the proposed model on a neo-nazi underground forum, IronMarch. </p>
  We first modeled the hackforum into a homogeneous graph of users, where the multiple edges between users are captured based on their involvement in private conversations, group discussions and other miscellaneous activities. 
  In addition, we also encode the textual content shared among users' in form of distributed feature representation generated from BERT.
  To obtain ground truth labels for training data, we propose a hypothesis to calculate the scores for each user based on the quality and quantity of their involvement in the underground forum. 
  The proposed framework jointly embeds the users' and multi relational information to learn the nodes embeddings in the graph. 
  We demonstrate the effectiveness of the proposed model on a neo-nazi underground forum, IronMarch.

<br>

### Technical Details
<ul>
<li>Language: Python</li>
<li>Semi-Supervised Learning </li>
<li>BERT for Language Modeling</li>
<li>Framework: Keras and Tensorflow</li>
<li>Model: Graph Convolutional Layer</li>
<li>Loss Function: Mean Squared Error</li>
</ul>

<br>

### Results
We conducted an ablation study on the model
  parameters to generate the best results and achieved
  a classification accuracy of 82% which validates the
  proposed hypothesis for score computation and class
  labelling. To establish the robustness of our model, we
  compare its performance against state-of-art models.
  Though we used an underground forum as a showcase,
  the proposed model can be implemented to identify
  influential users' on other social media platforms.

<!-- <p class="text-center">
{% include elements/button.html link="https://github.com/nikita-0209/kad_mrgcn_public" text="Code" %}
</p>

<p class="text-center">
{% include elements/button.html link="https://ieeexplore.ieee.org/document/9671446" text="Paper" %}
</p> -->