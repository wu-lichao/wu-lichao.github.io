---
title: "It’s a Kind of Magic: A Novel Conditional GAN Framework for Efficient Profiling Side-Channel Analysis"
collection: publications
category: conferences
permalink: /publication/asiacrypt24_gan_sca
date: 2024-12-01
venue: 'ASIACRYPT 2024'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-96-0944-4_4'
---

Profiling side-channel analysis (SCA) is widely used to evaluate the security of cryptographic implementations under worst-case attack scenarios. This method assumes a strong adversary with a fully controlled device clone, known as a profiling device, with full access to the internal state of the target algorithm, including the mask shares. However, acquiring such a profiling device in the real world is challenging, as secure products enforce strong life cycle protection, particularly on devices that allow the user partial (e.g., debug mode) or full (e.g., test mode) control. This enforcement restricts access to profiling devices, significantly reducing the effectiveness of profiling SCA.

To address this limitation, this paper introduces a novel framework that allows an attacker to create and learn from their own white-box reference design without needing privileged access on the profiling device. Specifically, the attacker first implements the target algorithm on a different type of device with full control. Since this device is a white box to the attacker, they can access all internal states and mask shares. A novel conditional generative adversarial network (CGAN) framework is then introduced to mimic the feature extraction procedure from the reference device and transfer this experience to extract high-order leakages from the target device. These extracted features then serve as inputs for profiled SCA. Experiments show that our approach significantly enhances the efficacy of black-box profiling SCA, matching or potentially exceeding the results of worst-case security evaluations. Compared with conventional profiling SCA, which has strict requirements on the profiling device, our framework relaxes this threat model and, thus, can be better adapted to real-world attacks.
