---
title: "The Best of Two Worlds: Deep Learning-assisted Template Attack"
collection: publications
category: conferences
permalink: /publication/tches22_constrastive_learning_sca
excerpt: false
date: 2022-06-08
venue: 'IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES)'
paperurl: 'https://tches.iacr.org/index.php/TCHES/article/view/9707/9237'
citation: false
---

In the last decade, machine learning-based side-channel attacks have become a standard option when investigating profiling side-channel attacks. At the same time, the previous state-of-the-art technique, template attack, started losing its importance and was more considered a baseline to compare against. As such, most of the results reported that machine learning (and especially deep learning) could significantly outperform the template attack. Nevertheless, the template attack still has certain advantages even compared to deep learning. The most significant one is that it has only a few hyperparameters to tune, making it easier to use.

We take another look at the template attack, and we devise a feature engineering phase allowing the template attack to compete or even outperform state-of-the-art deep learning-based side-channel attacks. More precisely, with a novel distance metric customized for side-channel analysis, we show how a deep learning technique called similarity learning can be used to find highly efficient embeddings of input data with one-epoch training, which can then be fed into the template attack resulting in powerful attacks
