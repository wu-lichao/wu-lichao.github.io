---
title: "Weakly Profiling Side-channel Analysis"
collection: publications
category: conferences
permalink: /publication/tches24_weakly_profiling_sca
excerpt: false
date: 2024-04-01
venue: 'IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES)'
paperurl: 'https://er.ceres.rub.de/index.php/TCHES/article/view/11901/11738'
citation: 'Wu, Lichao, Guilherme Perin, and Stjepan Picek. "Weakly Profiling Side-channel Analysis." IACR Transactions on Cryptographic Hardware and Embedded Systems 2024.3 (2024): 707-730.'
---

Profiling side-channel analysis, recognized for its robust attack performance in worst-case scenarios, necessitates adversaries to have a cloned device for profiling measurements and secret information for data labeling. On the other hand, nonprofiling attacks eschew these requirements by trying all key guesses. Although more suitable for real-world attack scenarios, they may suffer from mediocre attack performance due to the lack of leakage insight.
This paper introduces a novel weakly profiling side-channel analysis method that bridges classical profiling and non-profiling analyses. Our method operates within a profiling framework yet discards the necessity for a cloned device, which relies on the fact that there is (commonly) a bijective relationship between known information, such as plaintext and ciphertext, and secret information. This relationship allows an adversary to label leakage measurements using known information and then profile leakages directly on the attacked device. The empirical results show that the proposed approach achieves at least three times better attack performance with negligible computational effort than existing non-profiling methods. Moreover, it can rival the performance of state-of-the-art profiling attacks.
