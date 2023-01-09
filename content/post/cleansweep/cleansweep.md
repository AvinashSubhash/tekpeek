---
title: "Cleansweep"
date: 2023-01-06T13:25:23+05:30
draft: false
description: An Arch Linux tool to clean system, home directory cache, and duplicate files.
image: /cleansweep.png
categories:
    - Linux
    - Arch
---

# What exactly is CleanSweep ?

CleanSweep is a TUI program that helps newbie Arch Linux users to cleanup their system and clear up their precious memory. CleanSweep gives out a step by step process to user to the user with the ability for the user to skip a particular step.

# Why did I create this tool ?

In Arch Linux, as with any operating system, increasing cache memory can potentially improve system performance by allowing the system to store frequently accessed data in fast memory that can be quickly accessed. However, there are also potential drawbacks to increasing cache memory.

One potential problem with increasing cache memory is that it can potentially consume a large amount of physical memory, which could lead to increased competition for memory resources and potentially decreased performance if there is not enough available physical memory to meet the system's needs. Additionally, increasing cache memory may not always provide a noticeable improvement in performance, and in some cases it may even lead to decreased performance due to increased memory pressure.

If we go the manual way, we have to run several commands with pacman to clen cache, removed duplicate files etc, but with this one tool, we can go through all the cleaning process step by step with the ability to skip a particular step if not interested.

# How do I use this ?

I'ts pretty simple, go to `https://github.com/AvinashSubhash/CleanSweep` and follow the inctrustions written there.

