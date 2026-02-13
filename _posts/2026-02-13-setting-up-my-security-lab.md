---
title: Setting Up My Cloud Security Lab on GCP, Azure, and AWS.
date: 2026-02-13 10:07:00 +0300
categories: [Cloud, Lab-Setup, Azure, AWS, GCP]
tags: [ubuntu, nginx, gcp, aws, azure]
pin: true
image:
  path: /assets/awsgcpazure.jpg
  alt: A feature image for awsgcpazure.

---
## Why I Built This Lab
To truly understand  **Network Security**, I decided to move away from local VMs and Deploy a dedicated environment on **GCP AZURE and AWS** 
![Desktop View](/assets/awsgcpazure.jpg)
_This is the caption that appears centered under the image_

### Thee Architecture
I am currently running on **Ubuuntu 22.04** instance named *lab1*. My goals for this setup Include:
1: Configuring hardened *Nginx* Reverse Proxy.
2: Managing Access via *Custom SSH Ports* to reduce bruteforce noise.
3: Hosting my technical documentation (this blog!) via Github Pages.

### Lessons Learned
During this setup, I encountered issues with **BitLocker** encrypted drives on my local machine.

--- 
*Stay tuned for my next post*
