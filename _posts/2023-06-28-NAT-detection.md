---
layout: post
title: Detecting IP-tracking proof interfaces by looking for NATs
subtitle: Find out if you're alone behind your NAT
tags: [blog]
comments: true
---

The extended abstract for our poster presented at the [TMA Conference 2023](https://tma.ifip.org/2023/) is now available [here](/assets/pdf/tma2023poster-final4.pdf).

## Abstract

In this poster, we propose an approach based on short-lived random identifiers to allow applications to detect when multiple users share the same IP address such as when they are behind NATs. Using NATed interfaces could provide a cheap way to evade IP-based tracking as the traffic of all users is merged into a single IP flow. As a result, it is harder for trackers to single out (and so re-identify by IP address) users behind a NAT. For many years, there has been a race between web trackers trying to find techniques to monitor user behaviour online, and privacy researchers looking for solutions to avoid such tracking. Despite progresses in browser privacy-preserving techniques, IP tracking is still highly effective because current solutions to hide an IP address such as VPNs, or the Tor network, rely on external services and often induce a high cost in terms of performance. Our proposal could lead to solutions that are cheaper to deploy and don’t affect the performance as much. We developed an Android application detecting when an IP address was shared by multiple devices and reported the availability of such interfaces. We show that it is possible to identify networks where multiple users share the same IP address. We also discuss how our system can be protected from potential attackers.