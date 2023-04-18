---
layout: page
title: Nat Detection Application
subtitle: Protecting against IP Tracking using NAT interfaces
comments: true
---

For many years, there has been a race between webtrackers  trying  to  find  techniques  to  monitor  users  behaviouronline and privacy researchers looking for solutions to avoid suchtracking. Despite many progresses in browsers privacy preservingtechniques,  IP  tracking  remains  very  effective  because  currentsolutions to hide an IP address such as VPNs or the Tor networkrely  on  external  services  and  often  induce  a  high  cost  in  termsof  performance. 

We  proposed  an  approach  basedon  short-lived  random  identifiers  to  allow  applications  to  detect and  opportunistically  use  networks  where  multiple  users  sharethe  same  IP  address  such  as  Carrier-grade  NATs.  Using  thesenetworks allows to evade the trackers as the traffic of all users ismerged into a single IP flow. User traffic is then harder to single out. We developed an Android application using this method in order to obtain measures on the feasability and potential gain of the technique.

This application generates random identifiers and periodically sends them to a reporting server.
The server stores the identifiers and the IP addresses used to send them in order to study if IP tracking mechanism can uniquely identify a given user.
All information you provide will be treated anonymously and confidentially. Neither your name nor your contact details will be collected, stored nor made public.
We will also keep confidential all the IP addresses and the identifiers gathered during the measurements. Only dummy values will be used to illustrate approaches, theories or model.
If you have any question regarding the application or the data collected, feel free to contact us at.

The link to download the application is available [here](/assets/apk/app-apk.apk).