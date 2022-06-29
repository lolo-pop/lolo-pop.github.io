---
title: "Exploring the Layered Structure of Containers for Design of Video Analytics Application Migration"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Keywords: Edge computing, Video analytics application, Container migration'
date: 2022-03-15
venue: ' IEEE Wireless Communications and Networking Conference (WCNC)'
paperurl: ''
citation: 'Rong, Chenghao, Jessie Hui Wang, Juncai Liu, Tao Yu, and Jilong Wang. "Exploring the Layered Structure of Containers for Design of Video Analytics Application Migration." In 2022 IEEE Wireless Communications and Networking Conference (WCNC), pp. 842-847. IEEE, 2022.'
---

Abstract: The existing solutions to the migration of container-based applications are not suitable for live video analytics applications because these solutions can result in excessive migration time. Intuitively, it is possible to exploit the layered structure of containers to improve the migration performance, but we still need a good understanding of the characteristics of the containers related to video analytics applications to justify the intuitive idea and design a high-performance solution. In this paper, we pull 3735 representative images from Docker Hub. We analyze these images and get three main findings: (1) the images of video analytics applications have more layers and larger sizes than that of general applications; (2) we can cache images in the destination servers and reuse the same layers cached in the destination server to reduce the migration time when an image is migrated from its source server to its destination server; (3) the size of the remaining data to be transferred during migrations is still large and a high-performance migration scheme is still necessary. Based on the above findings, we propose a pipelined migration scheme to optimize migration performance. Evaluations show that pipelined migration performs significantly better than other migration schemes.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9771659/)

