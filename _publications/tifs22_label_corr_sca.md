---
title: "Label Correlation in Deep Learning-Based Side-Channel Analysis"
collection: publications
category: manuscripts
permalink: /publication/tifs22_label_corr_sca
excerpt: false
date: 2023-06-19
venue: 'IEEE Transactions on Information Forensics and Security (TIFS)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10155470'
citation: false
---

The efficiency of the profiling side-channel analysis can be significantly improved with machine learning techniques. Although powerful, a fundamental machine learning limitation of being data-hungry received little attention in the side-channel community. In practice, the maximum number of leakage traces that evaluators/attackers can obtain is constrained by the scheme requirements or the limited accessibility of the target. Even worse, various countermeasures in modern devices increase the conditions on the profiling size to break the target. This work demonstrates a practical approach to dealing with the lack of profiling traces. Instead of learning from a one-hot encoded label, transferring the labels to their distribution can significantly speed up the convergence of guessing entropy. By studying the relationship between all possible key candidates, we propose a new metric, denoted Label Correlation (LC), to evaluate the generalization ability of the profiling model. We validate LC with two common use cases: early stopping and network architecture search, and the results indicate its superior performance.