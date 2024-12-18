---
title: "Latency-Aware Strategies for Placing Data Stream Analytics onto Edge Computing"
collection: publications
category: posters
permalink: /publications/hotedge2018
venue: "HotEdge 2018"
date: 2018-6-12
paperurl: 'http://aveith.github.io/files/hotedge2018.pdf'
slidesurl: 
citation: '<b>da Silva Veith, Alexandre</b>; Dias de Assuncao, Marcos; Lefevre, Laurent'
---
[[Paper]](http://aveith.github.io/files/hotedge2018.pdf)



## Abstract
Much of the "big data" generated today is received in near real-time and requires quick analysis. In Internet of Things (IoT), for instance, continuous data streams produced by multiple sources must be handled under very short delays. As a result, several stream processing engines have been proposed. Under several engines, a stream processing application is a directed graph or dataflow whose vertices are operators that execute a function over the incoming data and edges that define how data flows between them. A dataflow has one or multiple sources (i.e., sensors, gateways or actuators), operators that perform transformations on the data (e.g., filtering, mapping, and aggregation) and sinks (i.e., queries that consume or store the data). In a traditional cloud deployment, the whole application is placed in the cloud computing to benefit from virtually unlimited resources. However, processing all the data in the cloud can introduce latency due to data transfer, which makes near real-time processing difficult to achieve. In contrast, edge computing has become an attractive solution for performing certain stream processing operators, as many edge devices have non-trivial compute capacity. The deployment of data stream processing applications onto heterogeneous infrastructure has been proved to be NP-hard. Moving operators from cloud to edge devices is challenging due to limitations of edge devices. Existing work often proposes placements strategies considering user intervention. Many models do not support memory and communication constraints while others consider all data sinks to be located in the cloud, with no feedback loop to actua-tors located at the edge of the network. There is a lack of solutions covering scenarios involving smart cities, precision agriculture, and smart homes comprising various heterogeneous sensors and actuators, as well as, time-constraint applications. We model the data stream processing placement problem considering heterogeneous computational and network resources, and computing and communication as M/M/1 queues (i.e., Poisson arrival distribution, exponential service time and single server). Events are handled in a First-Come, First-Served fashion both by the computation and communication services, guaranteeing the time order of events; an important requirement in many data stream processing applications. The model allows us to calculate the waiting and service times for each message in computation and communication queues allowing for estimating the response time. We then propose two strategies to minimize the application response time by splitting the dataflow graph dynamically and distributing the operators across cloud and edge infrastructure. We focus on real-time analytics applications with multiple sources and sinks distributed across resources. In particular, we first decompose the application graph by considering behaviors such as forks and joins (i.e., split points), and by identifying the operator dependencies recursively. The Response Time Rate (RTR) strategy takes the decomposed graph and organizes the deployment sequence and consecutively calculates the response time for each operator by considering the previous mappings, resource capabilities, and operator requirements. RTR with Region Patterns (RTR+RP) strategy extends RTR by exploiting the split points to first find candidate operators for edge or cloud and then estimates the response time for the edge operators. Comprehensive simulations considering multiple application configurations demonstrate that our approach can improve the response time up to 50%. For future work, we will investigate further techniques to deal with CPU-intensive operators and their energy consumption.




