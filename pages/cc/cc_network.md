---
title: Network 
keywords: cloud, introduction
last_updated: October 6, 2016
tags: [research_computing]
summary: "Cloud computing network connection"
sidebar: mydoc_sidebar
permalink: cc_network.html
folder: cc
---

## Introduction
This page documents network connection process, speed, details and benchmarks between our parent organization 
and public cloud vendors. That is: If you are a Researcher at UW and you need speed to connect to the cloud:
Start here. 


## Links
- [cloudmaven yeah!!!!](http://cloudmaven.org)
- [this page yeah!!!!](cc_network.html)


## Warnings
- ***We estabilsh both standard and accelerated network connection options here; the latter will probably
require installing some hardware and we indicate cost on the order of magnitude scale.***


## Glossary


- 10gig
- D528
- IDF
- fiber
- Cat6A copper


## AWS Case Study


This case study supports two light-sheet microscopes that generate several GB of data in 15 minutes. 
We need to get that data onto the AWS cloud in near-real-time. We have two locations: UW Health
Sciences D-Wing (HSD) and the Aeronautical Engineering Building AER.


Health Sciences D Wing (HSD) is ready to support 10gig: D528 is cabled to the telco closet / IDF in 
that area. Needed: Station cabling to D528 (longest lead-time item); and will this be copper or fiber?
With this information the Communications Infrastructure team works up an estimate and timeline. With
the cable in place the hardware follows quickly.  AER is more complex: A site visit is necessary to
determine whether there is room for the necessary hardware; again in an IDF / telco closet. 


Kilroy: Need a rough cost estimate for the necessary switch hardware, understanding the price 
may vary depending on fiber versus cat6a copper is to be used for the station cabling.  


## Ports, sockets and tunneling


This topic is related but does not belong on this page: It refers to access to instances inside the cloud; 
i.e. at a much higher level than basic network connectivity. For more on this please see [this page](cc_technical.html).


## Network poster


![cc_network_image_1](/documentation/images/cc/cc_network001.png)

![cc_network_image_2](/documentation/images/cc/cc_network002.png)


{% include links.html %}