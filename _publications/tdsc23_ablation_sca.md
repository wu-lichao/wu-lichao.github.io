---
title: "Ablation Analysis for Multi-Device Deep Learning-Based Physical Side-Channel Analysis"
collection: publications
category: manuscripts
permalink: /publication/tdsc23_ablation_sca
excerpt: false
date: 2023-05-22
venue: 'IEEE Transactions on Dependable and Secure Computing (TDSC)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10130619'
citation: false
---

The use of deep learning-based side-channel analysis is an effective way of performing profiling attacks on power and electromagnetic leakages, even against targets protected with countermeasures. While many research articles have reported successful results, they typically focus on profiling and attacking a single device, assuming that leakages are similar between devices of the same type. However, this assumption is not always realistic due to variations in hardware and measurement setups, creating what is known as the portability problem. Profiling multiple devices has been proposed as a solution, but obtaining access to these devices may pose a challenge for attackers. This article proposes a new approach to overcome the portability problem by introducing a neural network layer assessment methodology based on the ablation paradigm. This methodology evaluates the sensitivity and resilience of each layer, providing valuable knowledge to create a Multiple Device Model from Single Device (MDMSD). Specifically, it involves ablating a specific neural network section and performing recovery training. As a result, the profiling model, trained initially on a single device, can be generalized to leakage traces measured from various devices. By addressing the portability problem through a single device, practical side-channel attacks could be more accessible and effective for attackers.