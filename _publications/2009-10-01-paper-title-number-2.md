---
title: "Scheduling Massive Camera Streams to Optimize Large-Scale Live Video Analytics"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-2
excerpt: 'Keywords: Distributed computing, Edge computing, Video analytics, Scheduling, Task migration.'
date: 2021-10-01
venue: 'IEEE/ACM Transactions on Networking'
paperurl: ''
citation: 'Rong, Chenghao, Jessie Hui Wang, Juncai Liu, Jilong Wang, Fenghua Li, and Xiaolei Huang. "Scheduling Massive Camera Streams to Optimize Large-Scale Live Video Analytics." IEEE/ACM Transactions on Networking 30, no. 2 (2021): 867-880.'
---

Abstract: In smart cities, more and more government departments will make use of live analytics of videos from surveillance cameras in their tasks, such as vehicle traffic monitoring and criminal detection. Obviously, it is costly for each individual department to deploy its own infrastructure, i.e., cameras and analytics system. In this paper, we consider a scenario in which a city deploys an infrastructure and departments submit requests to access and analyze videos for their own purposes. The live analytics of massive streams is computation-intensive and the tasks might be latency-critical, which makes scheduling massive streams to optimize all tasks an essential and challenging work. We exploit an end-edge-cloud architecture and propose an adaptive system to schedule the massive camera streams and tasks, which considers all factors affecting the computation and networking resource consumption, e.g., sharing of model computation, video quality, model partition, and task placement. Particularly, the resource consumption of Faster R-CNN + ResNet101 under each partition scheme is profiled for the first time and we notice the partition must be used together with lossless compression techniques to be beneficial. Furthermore, sometimes tasks might be required to migrate because the scheduling decision made by the system changes to adapt to the changing resource supply and demand. In order to avoid the performance degradation during migration, we propose a non-destructive migration scheme and implement it in the system. Simulations demonstrate our system achieves a total utility close to the maximum and our analytics system performs better than state-of-the-art solutions.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9622882)
