---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Ph.D. candidate at ShanghaiTech University focusing on brain-computer interface system architecture. Research spans the full BCI stack: from EEG acquisition hardware (ADS1299, NRF52/53 series) to real-time signal processing, VR-integrated SSVEP paradigms, and closed-loop applications including drone and robotic arm control.

Education
======
* **Ph.D. Candidate in Computer Science and Technology**, ShanghaiTech University, 2021&nbsp;–&nbsp;present (expected Jul 2026)
  * Joint program with Shanghai Advanced Research Institute, Chinese Academy of Sciences
* **B.Eng. in Information Engineering**, Zhejiang University, 2017&nbsp;–&nbsp;2021

Skills & Research Scope
======
* **Research scope:** VR/AR-integrated BCI systems, wearable physiological sensing (EEG, ECG, EMG), edge computing, Internet of Brains (IoB)
* **Sensing & processing:** Analog/digital sensor integration; real-time signal processing and neural decoding; ML & DL model training and edge deployment; Non-invasive BCI paradigms (SSVEP/P300/MI)
* **System development:** End-to-end BCI prototyping: hardware (physiological signal acquisition, FPGA, MCU firmware), software (PC/Android applications, WiFi & BLE, Unity)
* **Tools & software:** EEG systems (Neuracle, Neuroscan, ADS1299); MATLAB, Python, PyTorch, EEGLAB, C++/C#, Unity; VR/AR headsets (HoloLens, Pico)

Research & Project Experience
======

### EEG Acquisition Platforms
* **2022–Present:** WiFi/BLE wearable EEG systems — ADS1299-based systems with WiFi/BLE streaming; developed PC host software and Unity interface
* **2024:** All-in-one multimodal physiological signal system — Zynq-based workstation with EEG/ECG/EMG, CCA-based SSVEP pipeline, and PyQt interface
* **2024–Present:** Bluetooth ear-EEG wearable — Swappable earcup module with miniaturized EEG (NRF52832/KS1092); developed companion app

### VR/AR BCI Integration
* **2022–2023:** Unity-based multi-scene VR-BCI platform — Unity platform with Neuroscan integration for SSVEP stimulus modulation and experiment control
* **2024:** Dual-layer binocular SSVEP encoding — Dual-layer VR encoding with binocular rivalry/fusion; managed IRB protocol and MATLAB/EEGLAB analysis
* **2023–2024:** End-to-end real-time SSVEP-BCI system — Unity pipeline with 8-target SSVEP, FBCCA algorithm, and trained NN model deployment via ONNX
* **2023–2024:** Standalone AR-BCI for Internet of Brains — HoloLens AR-BCI with Zigbee networking for wireless brain-to-brain communication

Professional Experience
======
* **2024–Present:** Co-founder & Technical Lead, GuoKe XinNao (Shanghai) Co., Ltd.
  * Leading R&D of ear-EEG wearable systems and commercialization of BCI technologies for daily-life applications
* **2025 Spring:** Course Development & TA, Brain-Computer Communication and Brain Internet
  * Authored BCI System Development chapter based on hands-on system prototyping experience
* **2023 Fall:** Teaching Assistant, Signals and Systems Lab, ShanghaiTech University

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards & Honors
======
* 2025 Shanghai Emerging Science and Technology Collaborative Innovation Competition, **First Prize** (GuoKe XinNao)
* 2025 Shanghai Industry Youth Innovation Competition, **Silver Prize** (GuoKe XinNao)
* 2025 Brain-Computer Interface Conference (BCIA, Shanghai), **Third Prize** in Brain-Controlled Vehicle and Robotic Arm Categories (Team Leader)
* ShanghaiTech University Academic Scholarship, 2021–2025

Academic Service
======
* **Peer Review:** *Biomedical Physics & Engineering Express*, *Journal of Neural Engineering*, *IEEE JBHI*, *Advanced Intelligent Systems*
* **Conference:** Poster presentation at 2025 "Smart Connection·Future" BCI International Conference, Hangzhou
* **Patents (2):** SSVEP-ERP based visual paradigm generation; AR brain-feedback interface system
