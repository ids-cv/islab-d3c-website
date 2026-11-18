---
title: 'PixCon: Pixel-Level Contrastive Learning Revisited'
authors:
- Zong-Shang Pang
- Yuta Nakashima
- Mayu Otani
- Hajime Nagahara
date: '2025-04-01'
publishDate: '2026-11-18T01:25:30.154932Z'
publication_types:
- article-journal
publication: '*Electronics*'
doi: 10.3390/electronics14081623
abstract: Contrastive image representation learning has been essential for pre-training
  vision foundation models to deliver excellent transfer learning performance. It
  was originally developed based on instance discrimination, which focuses on instance-level
  recognition tasks. Lately, the focus has shifted to directly working on the dense
  spatial features to improve transfer performance on dense prediction tasks such
  as object detection and semantic segmentation, for which pixel-level and region-level
  contrastive learning methods have been proposed. Region-level methods usually employ
  region-mining algorithms to capture holistic regional semantics and address the
  issue of semantically inconsistent scene image crops, as they assume that pixel-level
  learning struggles with both. In this paper, we revisit pixel-level learning’s potential
  and show that (1) it can effectively and more efficiently learn holistic regional
  semantics and (2) it intrinsically provides tools to mitigate the impact of semantically
  inconsistent views involved with scene-level training images. We prove this by proposing
  PixCon, a pixel-level contrastive learning framework, and testing different positive
  matching strategies based on this framework to rediscover the potential of pixel-level
  learning. Additionally, we propose a novel semantic reweighting approach tailored
  for pixel-level learning-based scene image pre-training, which outperforms or matches
  the performance of previous region-level methods in object detection and semantic
  segmentation tasks across multiple benchmarks.
links:
- name: URL
  url: https://doi.org/10.3390/electronics14081623
---
