---
title: "Heterogeneity analysis of acute exacerbations of
chronic obstructive pulmonary disease and a deep
learning framework with weak supervision and
privacy protection"
collection: publications
permalink: /publication/paper3
excerpt: ''
date: 2023-12-05
venue: ''
paperurl: 'http://yuto_suzuki.github.io/files/AECOPD_paper_12_7_2023.pdf'
citation: 'Yuto Suzuki, Andrew Hill, Elena Engel, Gregory Lyng, Ann Grancelli, Gabe Lockhart, Farnoush Banaei-Kashani, Russell Bowler(2023)'
---


Chronic obstructive pulmonary disease (COPD) affects 5-10% of the adult US
population and is a major cause of mortality. Acute exacerbations of COPD
(AECOPDs) are a major driver of COPD morbidity and mortality, but there
are no cost-effective methods to identify early AECOPDs when treatment is
most likely to reduce the severity and duration of AECOPDs.


We conducted the first long-term (> 12 months), real-time monitoring studies of
AECOPD with wearable sensors and self-reporting. We applied a deep learningbased autoencoder for feature extractions, then applied K-means clustering to
detect heterogeneity. Accordingly, we proposed a weakly supervised active learning framework to develop anomaly detection models for robust identification
of early AECOPD, and a clustered federated learning approach to personalize
the anomaly detection models for early detection of heterogeneous subtypes of
AECOPD. We evaluated this model by comparing it with other unsupervised
learning models and federated learning models.


We identified two clusters based on the Silhouette score and SHAP analysis.
We also found out that a single subject could have exacerbation events from
both clusters, indicating that there is not only subject-level heterogeneity but
also event-level heterogeneity. Our weakly supervised framework outperformed
unsupervised methods by 0.06 in average precision with 25 human annotation
labels per subject. Our federated learning framework outperformed standard
federated learning methods by 0.14 in F1 score and 0.17 in average precision.

We showed subject-level and event-level heterogeneity in AECOPD using mobile
and wearable device data and developed a practical AECOPD detection framework with limited human annotated labels and keeping data private in each
device.

[Download paper here](http://yuto_suzuki.github.io/files/AECOPD_paper_12_7_2023.pdf)

