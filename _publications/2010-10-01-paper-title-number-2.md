---
title: "Clustered Federated Learning for Heterogeneous Feature Spaces using Siamese Graph Convolutional Neural Network Distance Prediction"
collection: publications
permalink: /publication/paper2
excerpt: ''
date: 2023-07-02
venue: 'Federated Learning Systems (FLSys) Workshop@ MLSys 2023'
paperurl: 'https://openreview.net/forum?id=R5n5-Kq7Hlp'
citation: 'Y Suzuki, F Banaei-Kashani - … Learning Systems (FLSys) Workshop@ MLSys 2023, 2023'
---
Federated learning (FL) has been proposed to enhance performance of local machine learning models across multiple devices while maintaining data privacy. One of the main challenges in FL is data heterogeneity, which limits the benefits of knowledge exchange among federated models. Data heterogeneity is a two-fold problem: Non-IID (not independent and identically distributed) data, and heterogeneous feature space. While personalized federated learning (PFL) solutions address challenges with non-IID data, most of the solutions require the same feature space. The few PFL solutions that are applicable in feature heterogeneity scenarios map all local domains into a new common feature space, which may result in degraded performance because of the negative transfer effects from unrelated local models based on a very different feature space. To address this limitation, we propose a novel clustered federated learning based on a Siamese graph convolutional neural network (FedSGCNN). We predict positive transfer between clients using an SGCNN in order to create a distance matrix for clustering. This network-based prediction is more accurate as compared to other distance measures which fail to capture the structure of models. When there is feature space heterogeneity, we show that FedSGCNN outperforms the latest work by 1.2% in the Boston Housing dataset and 2.8% in the Obesity Level dataset.

[Download paper here](https://openreview.net/forum?id=R5n5-Kq7Hlp)

Recommended citation: Y Suzuki, F Banaei-Kashani - … Learning Systems (FLSys) Workshop@ MLSys 2023, 2023 