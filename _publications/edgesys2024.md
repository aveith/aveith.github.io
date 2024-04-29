---
title: "[PathFS: A File System for the Hierarchical Edge](https://dl.acm.org/doi/10.1145/3642968.3654822)"
collection: publications
permalink: /publications/edgesys2024
venue: "EdgeSys '24: Proceedings of the 7th International Workshop on Edge Systems, Analytics and Networking"
date: 2024-04-04
citation: 'Dantas de Lima Melo, Vinicius; Thiessen , Myles; Panas, Aleksey; <b>da Silva Veith, Alexandre</b>; Yano, Keijiro;  Balmau, Oana; de Lara, Eyal.'
---
[[Paper]](http://aveith.github.io/files/edgesys2024.pdf) [[BIBTEX]](http://aveith.github.io/files/edgesys2024.bib)



## Abstract
As IoT devices multiply and produce vast volumes of data, there is a heightened demand for instantaneous data processing. However, traditional cloud computing cannot adequately address these demands due to its latency and bandwidth limitations. Edge computing has emerged as a viable alternative with a hierarchical deployment of datacenters. However, this introduces additional layers of infrastructure and management that increase application development complexity. Using a shared file system is an attractive method for enhancing communication between components in an edge computing application.

In this paper we introduce PathFS, a shared file system designed for the hierarchical edge-cloud infrastructure. PathFS adopts a tree-like structure, with cloud datacenters at the root, edge datacenters as leaves, and a variable number of network datacenters in between. We evaluate PathFS through benchmarks on an emulated hierarchical edge deployment and compare it with NFS and ownCloud. The results show that PathFS offers lower latency than these systems by an order of magnitude, and scales to a larger number of concurrent clients without performance impacts, providing an end-to-end latency reduction of at least 80%.

