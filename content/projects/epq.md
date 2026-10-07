---
title: Securing A network using a Raspberry Pi 
Description: "Notes of EPQ"
date: 2026-03-31
tags:
- bash
- docker
- system administration
- packet inspection
- dns
---
## Project Overview
This was my EPQ and ended up getting a B. This was an artefact with the intention of improving network security and performance using a raspberry pi

To do this i used [Tailscale](https://tailscale.com/) to access my NAS at the time and other resources. In addition to [PiHole](https://pi-hole.net/) which is a DNS Sinkhole which allows me to block adverts and malicious websites

## Performance
I found that there was improvement is consistency with the ad-blocker and faster loading times for websites. Tailscale did lower speed and consistency but not enough to cause a noticeable difference in performance. I did speed test to prove this, find them below:

{{< speed-chart wifi-labels="None, VPN, Ad-Blocker, VPN+Ad-Blocker" ethernet-labels="None, VPN, Ad-Blocker, VPN+Ad-Blocker" >}}
