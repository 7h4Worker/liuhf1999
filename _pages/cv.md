---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Ph.D. candidate at ShanghaiTech University & SARI (CAS) in XR-based brain-computer interfaces. Research integrates VEP paradigm design, wearable neural sensing, and embedded system deployment toward practical BCIs. 

Education
=========

* **Ph.D. Candidate in Computer Science and Technology**, ShanghaiTech University, 2021&nbsp;–&nbsp;present (expected Jul 2026)
  * Joint program with Shanghai Advanced Research Institute, Chinese Academy of Sciences
* **B.Eng. in Information Engineering**, Zhejiang University, 2017&nbsp;–&nbsp;2021

Skills & Research Scope
=======================

* **Research scope:** XR-integrated BCI systems, wearable neural sensing (EEG/ECG/EMG), edge computing for real-time neural decoding, networked neural interfaces
* **Sensing & processing:** Analog/digital sensor integration; real-time signal processing and neural decoding; ML & DL model training and edge deployment; Non-invasive BCI paradigms (SSVEP/MI)
* **System development:** End-to-end BCI prototyping: hardware (physiological signal acquisition, FPGA, MCU firmware), software (PC/Android applications, WiFi & BLE, Unity)
* **Tools & software:** EEG systems (Neuracle, Neuroscan, ADS1299); MATLAB, Python, PyTorch, EEGLAB, C++/C#, Unity; VR/AR headsets (HoloLens, Pico)

Research & Project Experience
=============================

### EEG Acquisition Platforms

* **2022–Present:** Wireless EEG and ear-EEG wearable system — ADS1299-based wireless EEG with WiFi/BLE streaming and Unity integration; extended to miniaturized ear-EEG with swappable earcup module and companion app
* **2024:** Physiological signal acquisition workstation — Zynq-based EEG/ECG/EMG system with real-time bandpower computation, attention index output, CCA-based SSVEP decoding, and PyQt experiment interface

### VR/AR BCI Systems

* **2022–2024:** VR-SSVEP experimental platform with binocular mechanisms — Unity-based VR-BCI platform with Neuroscan integration; developed binocular SSVEP encoding exploiting stereoscopic disparity and rivalry for enhanced target discrimination; managed IRB protocol and full analysis pipeline
* **2023–2024:** SSVEP-BCI for Internet of Brain and Things — Wearable SSVEP-BCI system with Unity-based interface and ONNX-deployed neural network; demonstrated brain-controlled drone, robotic arm, and animal behavior modulation applications
* **2023–2024:** Standalone AR-BCI and Internet of Brains prototype — HoloLens-based AR-BCI with Zigbee networking for wireless brain-to-brain signal transmission

Professional & Teaching Experience
==================================

* **2024–Present:** Technical Lead, Ear-EEG Wearable Startup Project — Leading R&D of miniaturized ear-EEG system for consumer BCI applications; awarded First Prize in 2025 Shanghai Emerging Technology Competition
* **2025:** Technical Consultant & Project Lead — Designed and developed portable BCI demonstration kit: tablet-based Unity SSVEP system with wearable EEG for 8-command drone control, targeting education and outreach applications
* **2026 Spring:** Teaching Assistant, Brain-Computer Communication and Internet of Brain, ShanghaiTech University — Authored BCI System Development chapter based on hands-on system prototyping experience
* **2023 Fall:** Teaching Assistant, Signals and Systems Lab, ShanghaiTech University — Assignment grading, lab program tutoring, and course material preparation

Publications
============

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards & Honors
===============

* 2025 Shanghai Emerging Science and Technology Collaborative Innovation Competition, **First Prize**
* 2025 Shanghai Industry Youth Innovation Competition, **Silver Prize**
* 2025 Brain-Computer Interface Conference (BCIA, Shanghai), **Third Prize** in Brain-Controlled Vehicle and Robotic Arm Categories (Team Leader)
* ShanghaiTech University Academic Scholarship, 2021–2025

Academic Service
================

* **Peer Review:** *Biomedical Physics & Engineering Express*, *Journal of Neural Engineering*, *IEEE JBHI*, *Advanced Intelligent Systems*
* **Conference Presentations:** Poster presentation at 2025 "Smart Connection·Future" BCI International Conference and 1st China BCI Intelligence Conference, Hangzhou
