---
title: Point-Supervised Facial Expression Spotting with Gaussian-Based Instance-Adaptive
  Intensity Modeling
authors:
- Yicheng Deng
- Hideaki Hayashi
- Hajime Nagahara
date: '2026-01-01'
publishDate: '2026-07-23T03:38:49.325246Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Biometrics, Behavior, and Identity Science*'
doi: 10.1109/TBIOM.2026.3651893
abstract: 'Automatic facial expression spotting, which aims to identify facial expression
  instances in untrimmed videos, is crucial for facial expression analysis. Existing
  methods primarily focus on fully-supervised learning and rely on costly, time-consuming
  temporal boundary annotations. In this paper, we investigate point-supervised facial
  expression spotting (P-FES), where only a single timestamp annotation per instance
  is required for training. We propose a unique two-branch framework for P-FES. First,
  to mitigate the limitation of hard pseudo-labeling, which often confuses neutral
  and expression frames with various intensities, we propose a Gaussian-based instance-adaptive
  intensity modeling (GIM) module to model instance-level expression intensity distribution
  for soft pseudo-labeling. By detecting the pseudo-apex frame around each point label,
  estimating the duration, and constructing an instance-level Gaussian distribution,
  GIM assigns soft pseudo-labels to expression frames for more reliable intensity
  supervision. The GIM module is incorporated into our framework to optimize the class-agnostic
  expression intensity branch. Second, we design a class-aware apex classification
  branch that distinguishes macro- and micro-expressions solely based on their pseudo-apex
  frames. During inference, the two branches work independently: the class-agnostic
  expression intensity branch generates expression proposals, while the class-aware
  apex-classification branch is responsible for macro- and micro-expression classification.
  Furthermore, we introduce an intensity-aware contrastive loss to enhance discriminative
  feature learning and suppress neutral noise by contrasting neutral frames with expression
  frames with various intensities. Extensive experiments on the SAMM-LV, CAS(ME)$^2$,
  and CAS(ME)$^3$ datasets demonstrate the effectiveness of our proposed framework.'
links:
- name: URL
  url: https://doi.org/10.1109/TBIOM.2026.3651893
---
