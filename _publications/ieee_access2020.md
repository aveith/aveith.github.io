---
title: "[Boosting Big Data Streaming Applications in Clouds with BurstFlow](https://ieeexplore.ieee.org/document/9281110)"
collection: publications
permalink: /publications/ieee_access2020
venue: "IEEE Access 2020"
date: 2020-12-02
citation: 'De Souza Junior, Paulo R. R.; Matteussi, Kassiano J.; <b>da Silva Veith, Alexandre</b>; Zanchetta, Breno F.; R. Q. Leithardt, Valderi; Lozano M., Álvaro; P. de Freitas, Edison; dos Anjos, Julio C. S.; R. Geyer, Claudio F.'
---
[[Paper]](http://aveith.github.io/files/ieee_access2020.pdf) [[BIBTEX]](http://aveith.github.io/files/ieee_access2020.bib)



## Abstract
The rapid growth of stream applications in financial markets, health care, education, social media, and sensor networks represents a remarkable milestone for data processing and analytic in recent years, leading to new challenges to handle Big Data in real-time. Traditionally, a single cloud infrastructure often holds the deployment of Stream Processing  applications because it has extensive and adaptative virtual computing resources.  Hence, data sources send data from distant and different locations of the cloud infrastructure, increasing the application latency. The cloud infrastructure may be geographically distributed and it requires to run a set of frameworks to handle communication. These frameworks often comprise a Message Queue System and a Stream Processing Framework. The frameworks explore Multi-Cloud deploying each service in a different cloud and communication via high latency network links.  This creates challenges to meet real-time application requirements because the data streams have different and unpredictable latencies forcing cloud providers' communication systems to adjust to the environment changes continually. Previous works explore static micro-batch demonstrating its potential to overcome communication issues. This paper introduces BurstFlow, a tool for enhancing communication across data sources located at the edges of the Internet and Big Data Stream Processing applications located in cloud infrastructures. BurstFlow introduces a strategy for adjusting the micro-batch sizes dynamically according to the time required for communication and computation. BurstFlow also presents an adaptive data partition policy for distributing incoming streams across available machines by considering memory and CPU capacities. The experiments use a real-world multi-cloud deployment showing that BurstFlow can reduce the execution time up to 77% when compared to the state-of-the-art solutions, improving CPU efficiency by up to 49%.



