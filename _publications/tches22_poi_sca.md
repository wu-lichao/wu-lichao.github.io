---
title: "Exploring Feature Selection Scenarios for Deep Learning-based Side-channel Analysis"
collection: publications
category: conferences
permalink: /publication/tches22_poi_sca
excerpt: false
date: 2022-08-31
venue: 'IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES)'
paperurl: 'https://tches.iacr.org/index.php/TCHES/article/view/9842/9345'
citation: false
---

One of the main promoted advantages of deep learning in profiling sidechannel analysis is the possibility of skipping the feature engineering process. Despite that, most recent publications consider feature selection as the attacked interval from the side-channel measurements is pre-selected. This is similar to the worst-case security assumptions in security evaluations when the random secret shares (e.g., mask shares) are known during the profiling phase: an evaluator can identify points of interest locations and efficiently trim the trace interval. To broadly understand how feature selection impacts the performance of deep learning-based profiling attacks, this paper investigates three different feature selection scenarios that could be realistically used in practical security evaluations. The scenarios range from the minimum possible number of features (worst-case security assumptions) to the whole available traces. Our results emphasize that deep neural networks as profiling models show successful key recovery independently of explored feature selection scenarios against first-order masked software implementations of AES-128. First, we show that feature selection with the worst-case security assumptions results in optimal profiling models that are highly dependent on the number of features and signal-to-noise ratio levels. Second, we demonstrate that attacking raw side-channel measurements with small deep neural networks also provides optimal models, that shortens the gap between worst-case security evaluations and online (realistic) profiling attacks. In all explored feature selection scenarios, the hyperparameter search always indicates a successful model with up to eight hidden layers for MLPs and CNNs, suggesting that complex models are not required for the considered datasets. Our results demonstrate the key recovery with less than ten attack traces for all datasets for at least one of the feature selection scenarios. Additionally, in several cases, we can recover the target key with a single attack trace.
