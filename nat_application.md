---
layout: page
title: Nat Detection Application
subtitle: Protecting against IP Tracking using NAT interfaces - Find out if you're alone behind your NAT
comments: true
---

For many years, there has been a race between webtrackers  trying  to  find  techniques  to  monitor  users  behaviour online and privacy researchers looking for solutions to avoid such tracking. Despite many progresses in browsers privacy preserving techniques,  IP  tracking  remains  very  effective  because  current solutions to hide an IP address such as VPNs or the Tor network rely  on  external  services  and  often  induce  a  high  cost  in  terms of  performance. 

We  proposed  an  approach  based on  short-lived  random  identifiers  to  allow  applications  to  detect and  opportunistically  use  networks  where  multiple  users  sharethe  same  IP  address  such  as  Carrier-grade  NATs.  Using  these networks allows to evade some of the tracking as the traffic of all users is merged into a single IP flow. User traffic is then harder to single out. We developed an Android application using this method in order to obtain measurements on the feasability and potential gains of the technique.

This application generates random identifiers and periodically sends them to a reporting server.
The server stores the identifiers and the IP addresses used to send them in order to study if IP tracking mechanism can uniquely identify a given user.
All information you provide will be treated anonymously and confidentially. Neither your name nor your contact details will be collected, stored nor made public.
We will also keep confidential all the IP addresses and the identifiers gathered during the measurements. Only dummy values will be used to illustrate approaches, theories or model.
If you have any question regarding the application or the data collected, feel free to contact us at.

```
> Help our reasearch by installing our application ! The link to download the application is available [here](/assets/apk/app-apk.apk).
```
