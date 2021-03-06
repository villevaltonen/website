---
title: "Linux as a daily driver in 2020?"
date: 2020-02-02T00:20:00+02:00
description: "Why I switched to Linux? How's Linux in 2020? Do I miss something from Windows? A short summary of my experiences with Linux as my daily driver."
author: "Ville Valtonen"
draft: false
hidden: false
---

It has been few months now since I made the switch from Windows to Linux. I've had dual-boot of Windows 10 and Linux couple of times in the past at home, but last fall I did something completely new, I installed a Linux OS on my work machine for the first time ever. It was mainly because I started to encounter the limits of Windows more often and some of my colleagues were already using Linux in our corporate environment quite happily, so I thought that I'll give it a shot. In this post I'll share my experience with Linux so far.

### Why did I switch?

As a disclaimer, I don't hate or dislike Windows 10. I think it's pretty solid OS in general, but for my use, Linux is superior. In the beginning of this post I mentioned that I started to encounter the limitations of Windows more often. One of the those was that if I wanted to use Docker for Windows, I had to enable Hyper-V, which blocks the usage of any "level 2 hypervisors" like VirtualBox and VMWare. Other major reason for the switch was the integration of development tools and OS itself. Although Windows Subsystem for Linux (WSL) is one of the coolest pieces of technology that I've encountered lately, I wanted more integrated experience between my development tools and operating system. Dealing with WSL and Windows itself felt like dealing with two separate machines.

Those were the two main reasons I switched to Linux, but now that I've moved over, I've also noticed multiple other perks of using Linux for my work and personal projects. For example, Linux is fast. Like really fast. Compiling code, running tests, application and OS startup times, spinning up containers and so on. Everything is faster, which makes my workflow more enjoyable. Using Linux as a desktop OS is also a great learning experience. I've done a fair share of Linux server administration, but still, I learn new things on regular basis about the OS itself. I also like the level of control I have on my OS and the way that OS works in general.

### What could be better

It all sounds great, but are there any disadvantages or something I miss from Windows? Yes, there are couple of things, which are kind of interfering my otherwise smooth sailing with Linux-ship. The first one, cloud storage synchronization. I've been using OneDrive for few years and I really like how OneDrive is mounted into the filesystem in Windows and how it handles the synchronization on both ways. So far I've not yet found anything as convenient cloud storage solution for Linux so I've continued using OneDrive through the web interface on Linux. The second thing is only work related and hopefully will be a distant memory in the future, but the lack of Skype for Business support is causing some additional work, since now I have to start up a Windows 10 virtual machine to be able to attend a Skype-meeting. Luckily Microsoft Teams has started to replace Skype in many occasions and the Teams web application is quite good and there is even a native application for Linux as well.

### Final words

To summarize it, Linux (more specifically Debian) is a great OS for my needs and I will continue using it as my daily driver. Sure, there are couple of things that could be better, but the overall experience is really nice. I haven't had anything major issues, the operating system is really stable and fast and the hardware support is great. If you have thought about switching to Linux, I can highly recommend it. But buyer's beware, it's a captivating journey!

PS. If you're more interested in my setup, you can found it from [here](/posts/setup). My dotfiles and setup scripts are also available at [Github](https://github.com/villevaltonen/dotfiles).
