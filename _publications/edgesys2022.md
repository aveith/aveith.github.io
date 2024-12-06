---
title: "[Combining DNN partitioning and early exit](https://dl.acm.org/doi/abs/10.1145/3517206.3526270)"
collection: publications
category: conferences
permalink: /publications/edgesys2022
venue: "EdgeSys '22: Proceedings of the 5th International Workshop on Edge Systems, Analytics and Networking"
date: 2022-04-04
citation: 'Ebrahimi, Maryam; <b>da Silva Veith, Alexandre</b>; Gabel, Moshe; de Lara, Eyal.'
---
[[Paper]](http://aveith.github.io/files/edgesys2022.pdf) [[BIBTEX]](http://aveith.github.io/files/edgesys2022.bib)



## Abstract
DNN inference is time-consuming and resource hungry. Partitioning and early exit are ways to run DNNs efficiently on the edge. Partitioning balances the computation load on multiple servers, and early exit offers to quit the inference process sooner and save time. Usually, these two are considered separate steps with limited flexibility. This work combines partitioning and early exit and proposes a performance model to estimate both inference latency and accuracy. We use this performance model to offer the best partitioned/early exit DNN based on deployment information and user preferences. Our experiments show that the flexibility in number and position of partitioning points and placement on available devices plays an important role in deciding the best output. In the future, we plan to turn this work into a "one-click" system to train and optimize models for edge computing.
