---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Overview

Most of my research has grown from a simple belief: wireless systems should be able to sense and understand their surroundings, not only transmit data. Over the years, I have worked on turning communication hardware that is normally passive into active sensing platforms, using a combination of RF and microwave engineering, signal processing, and machine‑learning‑based inference.

What ties my work together is a consistent focus on the physical layer. Rather than separating sensing, communication, and intelligence into different modules, I try to design systems where these elements are naturally combined using shared RF hardware. This approach keeps systems simple, practical, and realistic for deployment, while opening the door to large‑scale sensing capabilities embedded directly into wireless networks.

## Early Work in Wireless Communication Systems

My research career started with fundamental problems in MIMO‑OFDM communication systems, which remain central to modern wireless standards. At that stage, my focus was on developing algorithms that improve performance without increasing hardware or computational burden—a constraint that is easy to ignore in theory, but unavoidable in practice.

I worked on data‑aided channel estimation methods that combine pilot symbols with reliable data subcarriers to improve estimation accuracy while reducing pilot overhead. These techniques consistently outperform classical LS and LMMSE approaches and remain suitable for real‑time implementation. Alongside this, I spent significant effort addressing the peak‑to‑average power ratio (PAPR) problem in OFDM systems, proposing companding and precoding schemes based on gamma correction, orthogonal periodic functions, and predictive filtering. The goal throughout was the same: meaningful PAPR reduction without sacrificing spectral efficiency or error performance.

Security was another aspect I approached at the physical‑layer level. I developed multilevel chaotic encryption schemes for MIMO‑OFDM systems that enhance security while simultaneously reducing PAPR. This work shaped how I think about system design today—performance, efficiency, and security should be designed together, not treated separately.

## Moving Toward Sensing‑Centric RF Systems

Over time, my research direction naturally shifted toward sensing‑centric RF systems. The motivating question was straightforward but powerful: *can the same RF hardware used for communication also be used to sense the environment, without compromising connectivity?*

Exploring this question led to the development of dual‑functional antenna sensors, where antennas are no longer passive radiators but become sensing elements whose electromagnetic response changes when exposed to physical or chemical stimuli. I demonstrated that selective gas sensing and reliable wireless communication can coexist within the same RF structure, without the need for additional tuning circuits or performance trade‑offs.

## Microwave and Antenna‑Embedded Chemical Sensing

A large part of my doctoral research focused on microwave chemical sensing using antenna‑embedded structures functionalized with advanced materials. I worked with molybdenum disulfide (MoS₂), MoS₂/MoOₓ heterostructures, molecularly imprinted polymers, and carbon‑nanotube‑based composites, carefully studying how each material influences the electromagnetic response of the antenna.

Compared to conventional chemiresistive sensors, microwave antenna‑based sensors operate through changes in electromagnetic properties. This makes them faster, more stable, and inherently compatible with wireless readout. Using this approach, I demonstrated sensitive and repeatable detection of methanol, ethanol, isopropanol, and other volatile organic compounds, with detection limits well below safety thresholds. Long‑term measurements showed stable performance over extended periods, which is critical for real‑world applications.

## MIMO Microwave Sensors and Electronic‑Nose Systems

The most distinctive outcome of my PhD work was the development of the first microwave MIMO sensing framework, where multiple antenna elements are used together to detect, distinguish, and quantify chemical species. Moving from single‑sensor prototypes to multi‑antenna systems introduced practical challenges, including mutual coupling, cross‑sensitivity, and spatial interference.

I addressed these issues by combining careful RF hardware design with machine‑learning‑assisted inference. Compact array layouts were developed to control coupling, and lightweight learning models were trained directly on measured RF data to separate sensing effects from electromagnetic artifacts. The final result was a microwave MIMO electronic‑nose system capable of detecting multiple VOCs and estimating their concentrations with very high accuracy, while maintaining uninterrupted wireless communication.

This work led to multiple high‑impact journal publications and was nominated for a Best Doctoral Thesis Award in the sensor field. The complete system—spanning materials, antenna design, and inference algorithms—is currently under industrial patent evaluation and early‑stage commercialization.

## How I Use Machine Learning

I do not treat machine learning as a substitute for physical understanding. Instead, I use it as a compact inference layer that builds on electromagnetic insight. Feature selection is guided by physics, model complexity is kept low, and robustness to noise, drift, and hardware imperfections is always evaluated.

In practice, I work mainly with Python and MATLAB to develop signal‑to‑inference pipelines for classification, regression, and adaptive estimation using real measurement data. This keeps models interpretable, stable, and suitable for deployment on edge hardware.

## Funding, Translation, and Practical Impact

My research has been supported through competitive external funding, including a Norwegian Research Council project where I served as Principal Investigator. One of the prototypes I developed also received industrial funding, supporting patenting and early commercialization efforts targeting air‑quality monitoring, food safety, and health‑related sensing.

Beyond individual devices, I see this work as a stepping stone toward wireless networks that act as distributed sensing platforms, where massive MIMO arrays also serve as environmental sensors. This idea aligns naturally with smart‑city applications, sustainability goals, and public‑health monitoring.

## Long‑Term Research Direction

Looking forward, my long‑term goal is to contribute to AI‑enabled integrated sensing and communication (ISAC) for 6G and IMT‑2030. I am particularly interested in systems where sensing‑aware RF hardware, adaptive signal processing, and physics‑informed AI are designed together, allowing networks to respond intelligently to their environment in real time.

Ultimately, I aim to help build a wireless sensing fabric that makes practical use of existing communication infrastructure to monitor, protect, and optimize our surroundings, in support of resilient, sustainable, and human‑centered digital societies.
