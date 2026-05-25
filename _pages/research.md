---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Overview

My work focuses on wireless systems that extract information about their environment while operating as communication hardware. The emphasis is on the physical layer, where antennas, waveforms, and signal processing are designed together under practical constraints.  

The approach is straightforward: use the same RF chain for both sensing and communication, without relying on idealized assumptions or additional hardware blocks.

---

## OFDM and Communication Systems

I started with MIMO-OFDM systems, working on problems that remain relevant in current wireless standards. The focus was on improving system behavior while maintaining implementability.

I developed data-aided channel estimation methods that combine pilot symbols with reliable data subcarriers. This improves estimation accuracy and reduces pilot overhead compared to classical approaches. In parallel, I worked on peak-to-average power ratio reduction using companding, orthogonal basis functions, and predictive filtering. These methods reduce PAPR while preserving spectral efficiency and error performance.

I also explored physical-layer security through multilevel chaotic encryption schemes integrated into the signal structure. This work reinforced a consistent view of system design: performance, efficiency, and security must be addressed together.

---

## RF Sensing Using Antenna Systems

My research direction shifted toward sensing when I began working with antenna structures whose electromagnetic response changes with the surrounding environment.  

In these systems, the antenna acts as both radiator and sensor. This allows communication signals to carry environmental information without modifying the system architecture.

The main outcome of this work is that sensing can be embedded directly into RF hardware instead of treated as a separate module.

---

## Microwave Chemical Sensing

During my PhD, I developed microwave sensing systems using antenna structures functionalized with advanced materials, including MoS₂, MoS₂/MoOₓ heterostructures, molecularly imprinted polymers, and carbon-nanotube composites.

These sensors operate through changes in electromagnetic properties instead of resistance. The result is faster response, improved stability, and direct compatibility with wireless interrogation.

I demonstrated detection of volatile organic compounds such as methanol, ethanol, and isopropanol, with detection limits below safety thresholds and stable behavior over extended periods.

---

## MIMO RF Sensing Systems

A key outcome of this work is a microwave MIMO sensing framework, where multiple antenna elements are used jointly to detect and distinguish chemical species.

Extending from single sensors to arrays introduced several issues, including mutual coupling, cross-sensitivity, and interaction between sensing elements. These were addressed through compact antenna design and inference models trained on measured RF data.

The resulting system functions as a microwave electronic nose capable of multi-gas detection and concentration estimation while maintaining communication functionality. This work led to several journal publications, a PhD thesis nomination, and ongoing patent evaluation.

---

## Machine Learning in Practice

Machine learning is used as an inference layer built on top of electromagnetic behavior.

Feature design follows physical understanding of the system, and models are kept small enough for stable and interpretable operation. All models are trained and tested on measured data. The focus is on classification, regression, and adaptive estimation using Python and MATLAB.

---

## Systems and Applications

The work is carried out at the system level, from RF hardware to signal processing and inference.  

Applications include air quality monitoring, food safety, and health-related sensing. A broader direction is to extend these concepts to antenna arrays and massive MIMO systems, where wireless infrastructure can also serve as a distributed sensing platform.

---

## Research Projects and Funding

- **Machine Learning Assisted Signal Processing for Antenna-Sensor Arrays (MLSP-ASA)**  
  Research Council of Norway, Project No. 353890 (2024–2025)

- **Air Quality Monitoring using Massive MIMO Antennas (AQMA)**  
  Research Council of Norway, Project No. 324061 (2022–2025)

---

## Current Direction

Current work focuses on integrated sensing and communication under practical constraints. This includes sensing from communication signals, modeling hardware impairments, and building lightweight inference systems that operate on real data.

---

## Long-Term Direction

The long-term direction is to develop wireless systems that produce environmental information as part of normal operation. This aligns with integrated sensing and communication for 6G, where sensing, communication, and system-level decisions are coupled within the same architecture.
