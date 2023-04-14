---
layout: post
title: Master Thesis
subtitle: TCPLS evaluation & extension
tags: [blog]
comments: true
---

My master thesis about the evaluation and extensions to TCPLS is now available [here](https://dial.uclouvain.be/memoire/ucl/object/thesis:35507). 

## Abstract

TCPLS is a new protocol integrating TCP and TLS to provide transport services to applications while being resistant to middleboxes. In this thesis, we evaluate the first TCPLS prototype over two different aspects: the performance when using multiple streams and the portability to mobile devices. Our experiments highlighted the impact of the scheduling between streams on the performance and demonstrated that TCPLS could be used by an Android application to communicate with a server through cellular and WiFi networks. We also propose several extensions to the existing protocol to enable new services such as TCP information exchange, NAT detection and flow shaping. We integrated these extensions within the prototype to demonstrate their feasibility. Finally, we developed a protocol to create secured tunneled byte streams on top of TCPLS. We implemented a prototype of this protocol to evaluate its performance over different metrics: the goodput, the latency and the number of requests per second to demonstrate that it is usable. All the pieces of software that we used are publicly available.