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

* **2022–Present:** WiFi/BLE wearable EEG systems — ADS1299-based systems with WiFi/BLE streaming; developed PC host software and Unity interface
* **2024:** All-in-one multimodal physiological signal system — Zynq-based workstation with EEG/ECG/EMG, CCA-based SSVEP pipeline, and PyQt interface
* **2024–Present:** Bluetooth ear-EEG wearable — Swappable earcup module with miniaturized EEG; developed companion app

### VR/AR BCI Integration

* **2022–2024:** VR-SSVEP experimental platform — Unity-based VR-BCI with Neuroscan integration; developed binocular SSVEP encoding exploiting stereoscopic disparity and rivalry
* **2023–2024:** SSVEP-BCI for Internet of Brain and Things — Wearable SSVEP-BCI with ONNX-deployed neural network; demonstrated brain-controlled drone, robotic arm, and animal behavior modulation
* **2023–2024:** Standalone AR-BCI and Internet of Brains — HoloLens AR-BCI with Zigbee networking for wireless brain-to-brain signal transmission

Professional Experience
=======================

* **2024–Present:** Co-founder & Technical Lead, BCI Startup
  * Leading ear-EEG wearable R&D and BCI technology commercialization for consumer applications
* **2025:** Technical Consultant & Project Lead
  * Designed portable BCI demonstration kit: tablet-based Unity SSVEP system with wearable EEG for drone control
* **2026 Spring:** Teaching Assistant, Brain-Computer Communication and Internet of Brain, ShanghaiTech University
* **2023 Fall:** Teaching Assistant, Signals and Systems Lab, ShanghaiTech University

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
* **Conference:** Poster presentation at 2025 "Smart Connection·Future" BCI International Conference, Hangzhou
