---
title: "PipeCompress: Accelerating Pipelined Communication for Distributed Deep Learning"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-3
excerpt: 'Keywords: Distributed Learning, Communication Pipeline.'
date: 2022-04-15
venue: ' IEEE International Conference on Communications (ICC)'
paperurl: ''
citation: 'Juncai Liu, Jessie Hui Wang,Chenghao Rong, and Jilong Wang,“PipeCompress:AcceleratingPipelinedCommunicationfor Distributed Deep Learning.” In 2022 IEEE International Conference on Communications (ICC).'
---

Abstract: Distributed learning is widely used to accelerate the training of deep learning models, but it is known that communication efficiency limits the scalability of distributed learning systems. Current gradient compression techniques provide promising methods to reduce communication time, but the extra time incurred by compression is not negligible. After compression techniques are applied, the communication time is significantly reduced because the data size needed to communicate becomes much smaller, but compressing gradients is time-consuming and it becomes a new bottleneck. In this paper, we design and implement PipeCompress, a system to decouple compression and backpropagation operations into two processes and pipeline the two processes to hide compression time. We also propose a specialized inter-process communication mechanism based on the characteristics of DNN distributed training to improve the efficiency of passing messages between the two processes, which makes sure that the decoupling does not bring much extra interprocess communication time cost. As far as we know, this is the first work that notices the overhead of compression and pipelines backpropagation and compression operations to hide compression time in distributed learning. Experiments show that PipeCompress can significantly hide compression time, reduce iteration time, and accelerate the training process on various DNN models.

[Download paper here](null)

