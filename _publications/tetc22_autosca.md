---
title: "I Choose You: Automated Hyperparameter Tuning for Deep Learning-Based Side-Channel Analysis"
collection: publications
category: manuscripts
permalink: /publication/tetc22_autosca
excerpt: false
date: 2022-11-07
venue: 'IEEE Transactions on Emerging Topics in Computing (TETC)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9940958'
citation: false
---

Today, the deep learning-based side-channel analysis represents a widely researched topic, with numerous results indicating the advantages of such an approach. Indeed, breaking protected implementations while not requiring complex feature selection made deep learning a preferred option for profiling side-channel analysis. Still, this does not mean it is trivial to mount a successful deep learning-based side-channel analysis. One of the biggest challenges is to find optimal hyperparameters for neural networks resulting in powerful side-channel attacks. This work proposes an automated way for deep learning hyperparameter tuning based on Bayesian optimization. We build a custom framework denoted AutoSCA supporting machine learning and side-channel metrics. Our experimental analysis shows that our framework performs well regardless of the dataset, leakage model, or neural network type. We find several neural network architectures outperforming state-of-the-art attacks. Finally, while not considered a powerful option, we observe that neural networks obtained via random search can perform well, indicating that the publicly available datasets are relatively easy to break.