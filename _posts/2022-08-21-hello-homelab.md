---
layout: post
title: Hello HomeLab
categories: [homelab, hardware]
tags: [servers, dell, hp, proxmox]
---

![img-description](/assets/logo_def_transp.png)

# Welcome

Hello and welcome to my HomeLab docs site!

The idea of making an home laboratory, mini datacenter type for self hosting, came about when, for professional reasons while studying networks and data acquisition, I noticed that many people had this activity as an hobby. As programming is also an area that I dedicate myself to for many years, I thought it might be interesting to have my own infrastructure at home.

## Hardware

After a few months of research, carefully analyzing the hardware solutions presented by youtubers and technical articles, I decided to start my own lab.

Many of the existing projects are of the business type, in which semi-obsolete used equipment is purchased at low prices, with exaggerated capacities for this type of projects and that consume a lot of energy.
So, I found it much more interesting and appropriate to use sff(small form factor) computers , which with ram and adequate processor, can have good performances without spending a lot of energy.

### First aquisitions

* 1 Intel NUC 10 intel Core i7-10710U / 32Gb RAM / NVMe 1Tb + SSD 1Tb
* 1 Synology DS220+ (2x4Tb)

After setting up one node with the Intel NUC and a RAID 1 storage with Synology NAS, made a few more aquisitions to setup a small but versatile homelab:

* 1 Lenovo ThinkCentre M900 micro tiny Intel i5-6500T / 16GB RAM /240 Gb SSD
* 2 Dell Optiplex 7050 micro PC i5-6500T 32GB RAM / 240 SSD

Later added some cheap UPS and an 8-port 1Gb switch.

Here's the result:

![ppmatrix homelab V1.0](/assets/homelab_v10.jpg)

## Software

After reading the opinions of some self hosting lab owners, I decided to install proxmox has virtualization management system, which turned out to be an excellent choice, as it is easy to install and very intuitive to use.

On next post of this Blog, I will describe the installation process and some considerations about using proxmox, creating VM's, CT's and other stuff.
