---
title: Save 10 Watts of juice in your GPU !
published: 2026-08-06
tags: [gpu, power]
category: pc
draft: false
---

Did you know the configuration that comes by default in your GPU driver can be altered to increase the efficiency of your GPU processing power?

Lets say the manufacturer decided to configure the power draw like this:
- 1920Mhz GPU Clock -> 75 Watt usages

That 75 Watt is about 13% higher than what your GPU actually need in order to achieve 1920Mhz !

That means you can actually achieve 1920Mhz of GPU Clock without having to use that much of a juice. Give it 65 Watt and boom you will still get the same clock speed.

This practice is called **Undervolting**``** and is done by lowering the GPU Voltage.

:::Info
Undervolting is one way to reduce the power draw in your laptop thus making it run cooler. Increasing your laptop's lifespan.
:::

One of most popular Software that you can use for undervolting purpose is MSI Afterburner.

Here's my result on Undervolting a RTX 3050 Mobile GPU:

<img src="https://i.imgur.com/ZK8O43u.png" alt="Before After" width="691" height="140">

Voila ~90Mhz Higher and most importantly, ~10 Watts lower !

