---
title: "Reinforcement Learning for Hyperparameter Tuning in Deep Learning-based Side-channel Analysis"
collection: publications
category: conferences
permalink: /publication/tches21_rl_sca
excerpt: false
date: 2021-07-19
venue: 'IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES)'
paperurl: 'https://tches.iacr.org/index.php/TCHES/article/view/8989/8566'
citation: false
---

Deep learning represents a powerful set of techniques for profiling side-channel analysis. The results in the last few years show that neural network architectures like multilayer perceptron and convolutional neural networks give strong attack performance where it is possible to break targets protected with various countermeasures. Considering that deep learning techniques commonly have a plethora of hyperparameters to tune, it is clear that such top attack results can come with a high price in preparing the attack. This is especially problematic as the side-channel community commonly uses random search or grid search techniques to look for the best hyperparameters.

In this paper, we propose to use reinforcement learning to tune the convolutional neural network hyperparameters. In our framework, we investigate the Q-Learning paradigm and develop two reward functions that use side-channel metrics. We mount an investigation on three commonly used datasets and two leakage models where the results show that reinforcement learning can find convolutional neural networks exhibiting top performance while having small numbers of trainable parameters. We note that our approach is automated and can be easily adapted to different datasets. Several of our newly developed architectures outperform the current state-of-the-art results. Finally, we make our source code publicly available.
