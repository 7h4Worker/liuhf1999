---
title: "Design and Implementation of a Scalable and High-Throughput EEG Acquisition and Analysis System"
collection: publications
category: manuscripts
permalink: /publication/2024-scalable-eeg-platform
excerpt: 'Presents an FPGA-based modular EEG platform that supports high-throughput acquisition and analytics for research and clinical BCIs.'
date: 2024-05-15
venue: 'Moore and More'
slidesurl:
paperurl: 'https://doi.org/10.1007/s44275-024-00017-w'
citation: '<b>H. Liu</b>, Z. Zhu, Z. Wang, et al. (2024). &quot;Design and Implementation of a Scalable and High-Throughput EEG Acquisition and Analysis System.&quot; <i>Moore and More</i>, 1:14.'
header:
  teaser: pub_moore2024/workflow.jpg
---
![System Workflow]({{ '/images/pub_moore2024/workflow.jpg' | relative_url }})

![FPGA Architecture]({{ '/images/pub_moore2024/structure3_fpga.jpg' | relative_url }})

![SSVEP Layout and Stimulus]({{ '/images/pub_moore2024/ssvep_layout_stimulus.jpg' | relative_url }})

![SARI-BCI System]({{ '/images/pub_moore2024/saribci-1+2.jpg' | relative_url }})

![High-Throughput BCI Experiment]({{ '/images/pub_moore2024/exp_ht_bci.jpg' | relative_url }})

**Abstract**
Recent advances in neuroscience, neuromorphic intelligence, and brain–computer interface (BCI) technologies have created a need for fast, efficient, and convenient electroencephalogram (EEG) data acquisition systems. However, the existing equipment was limited in its flexibility, restricting non-invasive studies to research or medical settings. To address this issue, low-cost, compact EEG acquisition devices have been developed, allowing for frequent and flexible brain data acquisition in various scenarios. This paper introduces a scalable and high-throughput EEG signal acquisition and analysis system based on field-programmable gate array (FPGA) technology. The proposed system offers electrode scalability, on-chip computing, and optional wireless functionality extension. These features are achieved through the design of a highly scalable underlying EEG acquisition module and an FPGA central module that enables software-defined high-throughput expansion and high-speed data exchange between software and hardware. The paper presents two implementation cases that demonstrate the potential of the proposed system. The first case introduces a wearable wireless EEG system, enabling the deployment of effective and
user-friendly steady-state visual evoked potential (SSVEP)-BCI applications in consumer-grade scenarios. The second case integrates an FPGA central module with multiple basic EEG acquisition modules to construct a high-throughput BCI system for cost-effective and real-time EEG data acquisition and processing. This configuration allows for flexible deployment in research and clinical applications, including attention index, SSVEP, motor imagery (MI), and emotion recognition. This combination further demonstrates the potential of scalable EEG systems and emphasizes the need for further integration or chipization. These implementations validate the feasibility of compact and efficient EEG devices and highlight the promising applications of scalable BCI system in various fields.
