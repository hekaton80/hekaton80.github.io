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

After reading about self-hosters choice for virtualization engine, I decided to install proxmox, and it revealed to be a good choice.
Easy to install and intuitive management. 






```javascript
console.log('hello World'):
```
```yml
version: '3.3'
services:
    dashy:
        ports:
            - '8088:80'
        volumes:
            - '/home/paulo/dashy-data/my-config.yml:/app/public/conf.yml \'
        image: 'lissy93/dashy'
        restart: always
```
```python
def delocalize(string):
    "Parses a string as a normalized number according to the locale settings."

    conv = localeconv()

    #First, get rid of the grouping
    ts = conv['thousands_sep']
    if ts:
        string = string.replace(ts, '')

    #next, replace the decimal point with a dot
    dd = conv['decimal_point']
    if dd:
        string = string.replace(dd, '.')
    return string

print(delocalize('12,6'))
```
