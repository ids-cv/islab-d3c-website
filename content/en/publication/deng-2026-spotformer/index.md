---
title: 'SpotFormer: Multi-Scale Spatio-Temporal Transformer for Facial Expression
  Spotting'
authors:
- Yicheng Deng
- Hideaki Hayashi
- Hajime Nagahara
date: '2026-01-01'
publishDate: '2026-07-23T03:38:47.260633Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Affective Computing*'
doi: 10.1109/TAFFC.2026.3677401
abstract: Facial expression spotting, identifying periods where facial expressions
  occur in a video, is a significant yet challenging task in facial expression analysis.
  The issues of irrelevant facial movements and the challenge of detecting subtle
  motions in micro-expressions remain unresolved, hindering accurate expression spotting.
  In this paper, we propose an efficient framework for facial expression spotting.
  First, we propose a Compact Sliding-Window-based Multi-temporal-Resolution Optical
  flow (CSW-MRO) feature, which calculates multi-temporal-resolution optical flow
  of the input image sequence within compact sliding windows. The window length is
  tailored to perceive complete micro-expressions and distinguish between general
  macro- and micro-expressions. CSW-MROcan effectively reveal subtle motions while
  avoiding the optical flow being dominated by head movements. Second, we propose
  SpotFormer, a multi-scale spatio-temporal Transformer that simultaneously encodes
  spatio-temporal relationships of the CSW-MROfeatures for accurate frame-level probability
  estimation. In SpotFormer, we use the proposed Facial Local Graph Pooling (FLGP)
  operation and convolutional layers to extract multi-scale spatio-temporal features.
  We show the validity of the architecture of SpotFormer by comparing it with several
  model variants. Third, we introduce supervised contrastive learning into SpotFormer
  to enhance the discriminability between different types of expressions. Extensive
  experiments on SAMM-LV, CAS(ME)2, and CAS(ME)3 show that our method outperforms
  state-of-the-art models, particularly in micro-expression spotting. Code is available
  at https://github.com/KinopioIsAllIn/SpotFormer.
---
