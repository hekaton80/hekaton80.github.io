---
title: Hello HomeLab
date: 2022.08.20 23:10:00 -500
categories: [homelab, hardware]
tags: [servers, dell, hp, proxmox]
---

# Welcome

Hello and welcome to my HomeLab docs site!

The idea of making an home laboratory, mini datacenter type, came about when, for professional reasons when studying networks and data acquisition, I noticed that many people had this activity as a hobby. As programming is also an area that I dedicate myself to for many years, I thought it might be interesting to have my own infrastructure at home.

# Hardware

After a few months of research, carefully analyzing the hardware solutions presented by youtubers and technical articles, I decided to start my own lab.

Many of the existing projects are of the business type, in which semi-obsolete used equipment is purchased at low prices, with exaggerated capacities for this type of projects and that consume a lot of energy.
So, I found it much more interesting and appropriate to use sffps , which with ram and adequate processor, can have good performances without spending a lot of energy.


* First aquisitions
My first choices were an intel nuc and a Synology NAS

![img-description](https://www.novoatalho.pt/Images/product/lg/PC00473_1_Zl17.jpg)

* two
* three
* four
* five
* six

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
