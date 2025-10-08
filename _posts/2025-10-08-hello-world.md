---
layout: post
title:  "Starting my cybersecurity homelab"
date:   2025-10-08 06:55:57 -0400
categories: [homelab,meta]
---
I am starting this blog as a way to take notes while I build and experiment with my virtual homelab. 

I'm currently studying for the Security+ certification, and this will help me gain a deeper understanding of many of the concepts with hands-on experience. Capturing these notes will help me formally document the project as it matures. 

It's mostly for myself-to keep track of what I've done and plan, but maybe somebody else will find it interesting.

<figure style="text-align:center;">
  <img src="{{ '/assets/img/homelab-2025-10-08.png' | relative_url }}" 
       alt="Homelab overview" 
       style="max-width:90%; border-radius:8px;">
  <figcaption><em>Initial layout of my GNS3 homelab.</em></figcaption>
</figure>

I'm using GNS3 on an Ubuntu host. I have machines for Kali, Metasploitable3, OWASP Juice Shop, as well as a Windows Server 2019 domain controller with an attached Windows 10 box.

Metasploitable and Juice Shop are intentionally vulnerable by design, and I set up some accounts on the AD domain that should be easy targets.

That's it for now. My next step is to install Wazuh for network monitoring, which I'm excited to try after reading some of the documentation. 
