---
title: "A Tunable Implementation of Quality-of-Service Classes for HPC Networks"
date: 2021-06-01
publishDate: 2021-04-12T03:50:28.600282Z
authors: ["Kevin A. Brown", "Neil McGlohon",  "Christopher D. Carothers", "Robert B. Ross", "Sudheer Chunduri", "Eric Borch"]
publication_types: ["1"]
abstract: "Quality of Service (QoS) solutions can regulate the allocation of resources by defining traffic classes with specified resource allocations and assigning applications to these classes, thus improving application performance predictability. However, it is difficult to accomplish facility-level goals of ensuring efficient application communication when constrained to a limited number of classes.

We propose a practical QoS implementation for large-scale, low-diameter networks, such as the dragonfly topology, using flexible bandwidth shaping along with traffic prioritization to reduce the impact of interference on communication performance. Our design gives facilities more control over tuning QoS class to meet application- and site-specific performance guarantees. The results show that our solution effectively eliminates the slowdown of high-priority traffic due to interference with lower-priority traffic, significantly reducing run-to-run variability. We also demonstrate how port counters can be used to detect when a job-to-class assignment is inappropriate for a given system and when a workload is exceeding the bandwidth limits of its class."
featured: true
publication: "*ISC High Performance 2021: High Performance Computing (ISC) - to be published.*"
tags: ["QoS", "dual rate traffic class", "1D dragonfly", "network", "simulation"]
---

