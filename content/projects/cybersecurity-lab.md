---
title: "Cybersecurity Lab"
description: "My practical set up for security and praticality"
date: 2026-09-15
tags:
- linux
- virtualisation
- dns
---
<!-- 
## Introduction
The aim of this project is to make me a practical and secure environment I can do my work. Here is how i did it

### Devices
#### Main Workstation
```
CPU: Ryzen 7 5700g 
GPU: Gigabyte Radeon RX 9060 XT GAMING OC 16G
RAM: 32 GB DDR4 3600 MHz CL18
```
### Optiplex 3010 (Server)
```
CPU: Intel i5-3570
GPU: Intel HD Graphics
RAM: 8 GB DDR3 1600 MHz CL11 
```

### Uni Laptop (Thinkpad T480)
```
CPU: Intel(R) Core(TM) i7-8550U 
GPU: Intel UHD Graphics 620
RAM: 16 GB DDR4 2400 MHz CL19
```
-->
## Network
I'm running [PfSense](https://www.pfsense.org/) on the [Optiplex](#optiplex-3010-server) in addition to [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) as a base for my network.

For hardware im using an unmanaged 8 port gigabit switch from TpLink and a 2.5 Gigabit PCI Express Ethernet Network Adapter for my LAN, using the inbuilt ethernet port as my WAN. I'm also planning to get a Wireless access point and perhaps terminate my own ethernet cables so I can perfect the lengths and make it look neat.

## Main workstation
```
CPU: Ryzen 7 5700g 
GPU: Gigabyte Radeon RX 9060 XT GAMING OC 16G
RAM: 32 GB DDR4 3600 MHz CL18
```
This will be my main workstation for doing work as out of my devices it has the best performance. As I'll be using it for personal use as well I'll be dualbooting [CachyOS](https://www.cachyos.org) (For personal use and gaming) and [Ubuntu LTS](https://ubuntu.com) (For work). I will have a files partition which both OS' will share. Most things such as games, VM disks and documents will be stored on the shared partition

I will be running atleast 1 [Kali Linux](https://www.kali.org) VM and 1 [Windows 11](https://www.microsoft.com/en-gb/windows/windows-11) VM. I'll probably also run things such as Metasploit.

## Optiplex 3010 (Server)
```
CPU: Intel i5-3570
GPU: Intel HD Graphics
RAM: 8 GB DDR3 1600 MHz CL11 
```
This Optiplex is being used as a server, I'm running [Proxmox](https://www.proxmox.com/en/) as the OS. At the moment It's just being used for the base of my [network](#network) but I do want to add more and this page will be updated as I do. 

## Thinkpad T480 (Uni Laptop)
```
CPU: Intel(R) Core(TM) i7-8550U 
GPU: Intel UHD Graphics 620
RAM: 16 GB DDR4 2400 MHz CL19
```
This laptop will run Ubuntu LTS and have a Kali and Windows 11 VM. I'll be bringing it to lectures to take notes and do more basic tasks.