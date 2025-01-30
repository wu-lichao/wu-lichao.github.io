---
title: "Plaintext-based Side-channel Collision Attack"
collection: publications
category: manuscripts
permalink: /publication/cic24_pscca
excerpt: false
date: 2024-09-02
venue: 'IACR Communications in Cryptology (CiC)'
paperurl: 'https://cic.iacr.org/p/1/3/20/pdf'
citation: false
---

Side-channel Collision Attacks (SCCA) is a classical method that exploits information dependency leaked during cryptographic operations. Unlike collision attacks that seek instances where two different inputs to a cryptographic algorithm yield identical outputs, SCCAs specifically target the internal state, where identical outputs are more likely. Although SCCA does not rely on the pre-assumption of the leakage model, it explicitly operates on precise trace segments reflecting the target operation, which is challenging to perform when the leakage measurements are noisy. Besides, its attack performance may vary dramatically, as it relies on selecting a reference byte (and its corresponding leakages) to “collide” other bytes. A poor selection would lead to many bytes unrecoverable. These two facts make its real-world application problematic.

This paper addresses these challenges by introducing a novel plaintext-based SCCA. We leverage the bijective relationship between plaintext and secret data, using plaintext as labels to train profiling models to depict leakages from varying operations. By comparing the leakage representations produced by the profiling model instead of the leakage segmentation itself, all secret key differences can be revealed simultaneously without processing leakage traces. Furthermore, we propose a novel error correction scheme to rectify false predictions further. Experimental results show that our approach significantly surpasses the state-of-the-art SCCA in both attack performance and computational complexity (e.g., training time reduced from approximately three hours to five minutes). These findings underscore our method's effectiveness and practicality in real-world attack scenarios.