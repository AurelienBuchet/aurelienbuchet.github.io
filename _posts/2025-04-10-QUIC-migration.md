---
layout: post
title: An Analysis of QUIC Connection Migration in the Wild
subtitle: A first look at QUIC connection migration
tags: [blog]
comments: true
---

Our paper "An Analysis of Quic Connection Migration in the Wild" has been published at [ACM SIGCOMM Computer Communication Review](https://ccronline.sigcomm.org/). You can find the full paper [here](https://dl.acm.org/doi/abs/10.1145/3727063.3727066).

## Abstract

As QUIC gains attention, more applications that leverage its capabilities are emerging. These include defenses against on-path IP tracking and traffic analysis. However, the deployment of the underlying required support for connection migration remains largely unexplored. This paper provides a comprehensive examination of the support of the QUIC connection migration mechanism over the Internet. We perform Internet-wide scans revealing that despite a rapid evolution in the deployment of QUIC on web servers, some of the most popular destinations do not support connection migration yet.