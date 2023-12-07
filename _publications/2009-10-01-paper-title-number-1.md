---
title: "Evaluation of Quantitative Decision‐Making for Rhythm Management of Atrial Fibrillation Using Tabular Q‐Learning"
collection: publications
permalink: /publication/paper1
excerpt: ''
date: 2023-5-02
venue: 'Journal  of the American Heart Association'
paperurl: 'https://www.ahajournals.org/doi/full/10.1161/JAHA.122.028483'
citation: 'CD Barrett, Y Suzuki, S Hussein, L Garg, A Tumolo… - Journal of the American Heart Association, 2023'
---

Abstract
Background
Rhythm management is a complex decision for patients with atrial fibrillation (AF). Although clinical trials have identified subsets of patients who might benefit from a given rhythm‐management strategy, for individual patients it is not always clear which strategy is expected to have the greatest mortality benefit or durability.

Methods and Results
In this investigation 52 547 patients with a new atrial fibrillation diagnosis between 2010 and 2020 were retrospectively identified. We applied a type of artificial intelligence called tabular Q‐learning to identify the optimal initial rhythm‐management strategy, based on a composite outcome of mortality, change in treatment, and sustainability of the given treatment, termed the reward function. We first applied an unsupervised learning algorithm using a variational autoencoder with K‐means clustering to cluster atrial fibrillation patients into 8 distinct phenotypes. We then fit a Q‐learning algorithm to predict the best outcome for each cluster. Although rate‐control strategy was most frequently selected by treating providers, the outcome was superior for rhythm‐control strategies across all clusters. Subjects in whom provider‐selected treatment matched the Q‐table recommendation had fewer total deaths (4 [8.5%] versus 473 [22.4%], odds ratio=0.32, P=0.02) and a greater reward (P=4.8×10−6). We then demonstrated application of dynamic learning by updating the Q‐table prospectively using batch gradient descent, in which the optimal strategy in some clusters changed from cardioversion to ablation.

Conclusions
Tabular Q‐learning provides a dynamic and interpretable approach to apply artificial intelligence to clinical decision‐making for atrial fibrillation. Further work is needed to examine application of Q‐learning prospectively in clinical patients.


[Download paper here](https://www.ahajournals.org/doi/full/10.1161/JAHA.122.028483)

Recommended citation: CD Barrett, Y Suzuki, S Hussein, L Garg, A Tumolo… - Journal of the American Heart Association, 2023