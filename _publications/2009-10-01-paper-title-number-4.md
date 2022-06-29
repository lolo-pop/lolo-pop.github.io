---
title: "FedPA: an Adaptively Partial Model Aggregation Strategy in Federated Learning"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-4
excerpt: 'Keywords: Federated Learning, Aggregation Strategy, Straggler Problem.'
date: 2021-11-09
venue: 'Computer Networks (CN)'
paperurl: ''
citation: 'Liu, Juncai, Jessie Hui Wang, Chenghao Rong, Yuedong Xu, Tao Yu, and Jilong Wang. "FedPA: An adaptively partial model aggregation strategy in Federated Learning." Computer Networks 199 (2021): 108468.'
---

Abstract: Federated Learning has sparked increasing interest as a promising approach to utilize large amounts of data stored on network edge devices. Federated Averaging is the most widely accepted Federated Learning framework. In Federated Averaging, the server keeps waiting for client models to compute the global model in each round unless all client models are received or a pre-configured timer expires, therefore it suffers seriously from participant devices with weak computation and/or communication capability, which is a kind of straggler problem. In this paper we design FedPA, a framework based on partial model aggregation strategy, in which the server waits for only an appropriate number of device models (referred to as aggregation number) in each round. Our experiment shows that the accuracy loss of the aggregated global model in a single round is not significant if the aggregation number is decided carefully. We propose a waiting strategy to determine the aggregation number for each round dynamically and the aggregation number is adaptive to achieve a tradeoff between single-round training time and the expected number of rounds to reach the target accuracy. Stale models are also included during aggregation when they arrive, and their positive value and negative effect are carefully evaluated and reflected in the aggregation strategy. Experiments show that FedPA outperforms the baseline strategy FedAvg and other three algorithms named FedAsync, FLANP and AD-SG. It can work well in all scenarios with different distributions of data samples (characterized by non-IID ratio) and computation/communication capability (characterized by level of heterogeneity) among devices. Experiments also show that FedPA is robust when a certain amount of noise is added into the input from clients for privacy concerns.

[Download paper here](https://www.sciencedirect.com/science/article/abs/pii/S1389128621004199)

