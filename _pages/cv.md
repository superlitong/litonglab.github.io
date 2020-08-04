---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download the pdf [here](/files/CV.pdf).

Education
======
* B.S. in Department of Computer Science and Technology, Wuhan University, 2012
* Ph.D in Department of Computer Science and Technology, Tsinghua University, 2017 

Work experience
======
* Jul. 2017 – to date: Senior Researcher
  * Computer Network and Protocol Lab, 2012 Laboratories, Huawei
  * Duties included: 
    * Measurement study on multi-path TCP with multiple cellular carriers on high-speed rails. Part of my work was done when I was a PhD student in Tsinghua University. This work is published on the [ACM SIGCOMM 2018](https://conferences.sigcomm.org/sigcomm/2018/).
    * Standardization of a novel acknowledgement mechanism, known as TACK (Tame ACKnowledgement), which is aimed to be the standard of acknowledgement in 802.11-based wireless scenarios (e.g., WLAN). We are active in IETF groups such as [tcpm](https://tools.ietf.org/id/draft-li-tcpm-advancing-ack-for-wireless-00.html) and [QUIC WG](https://tools.ietf.org/id/draft-li-quic-optimizing-ack-in-wlan-00.html).
    * I designed the TCP-TACK (UDP-based implementation is called FillP). TCP-TACK is a newly proposed transport protocol, revisiting division of labor between sender and receiver of TCP. TCP- TACK is now applied in dozens of Huawei products including smartphones, projection devices, CDNs, storage systems, applications, and internal tools. This work is published on the [ACM SIGCOMM 2020](https://conferences.sigcomm.org/sigcomm/2020/).
    * Team Leader of [Nearby Service](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/introduction-0000001050040566), which is one of 24 kits in the [Huawei Mobile Service](https://developer.huawei.com/consumer/en/hms) (HMS). Nearby Service allows apps to easily discover nearby devices and set up communication with them using technologies such as Bluetooth and Wi-Fi. The service provides [Nearby Connection APIs](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/connection-preparations-0000001050040586) and [Nearby Message APIs](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/message-preparations-0000001050042561).
    * Architect and product manager of [Contact Shield](https://developer.huawei.com/consumer/en/doc/development/Contact-Shield-V1/introduction-0000001050738511-V1). I led the team to design, implement, and release the HMS Core Contact Shield, which is a basic contact tracing service developed based on the Bluetooth low energy (BLE) technology. Government organizations can authorize developers to develop COVID-19 contact tracing apps using [Contact Shield APIs](https://developer.huawei.com/consumer/en/doc/development/Contact-Shield-V1/contactshield-overview-0000001051058454-V1). These apps can interact with other devices while protecting user privacy to check whether a user has been in contact with a person tested positive for COVID-19. If so, the user will be notified and instructed to take relevant measures, effectively controlling the spread of the virus.
  * Supervisor: Dr. Kai Zheng & Dr. Kun Tan


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
English skills
======
* Skilled English, can be used as a living and working language
* 10-month oversea study and work experience (United Kingdom)
* Certificate of the CET-4, CET-6, and Tsinghua English Proficiency Test II
