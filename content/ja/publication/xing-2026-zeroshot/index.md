---
title: Zero-shot Hierarchical Plant Segmentation via Foundation Segmentation Models
  and Text-to-image Attention
authors:
- Junhao Xing
- Ryohei Miyakawa
- Yang Yang
- Xin-Peng Liu
- Risa Shinoda
- Hiroaki Santo
- Yosuke Toda
- Fumio Okura
date: '2026-03-01'
publishDate: '2026-11-18T01:25:31.869784Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Winter Conference on Applications of Computer
  Vision (WACV)*'
doi: 10.1109/WACV61042.2026.00247
abstract: Foundation segmentation models achieve reasonable leaf instance extraction
  from top-view crop images without training (i.e., zero-shot). However, segmenting
  entire plant individuals with each consisting of multiple overlapping leaves remains
  challenging. This problem is referred to as a hierarchical segmentation task, typically
  requiring annotated training datasets that are often species-specific and require
  significant human labor. To address this, we introduce ZeroPlantSeg, a zero-shot
  segmentation for rosette-shaped plant individuals from top-view images. We integrate
  a foundation segmentation model, extracting leaf instances, and a vision-language
  model, reasoning about plants’ structures to extract plant individuals without additional
  training. Evaluations on datasets with multiple plant species, growth stages, and
  shooting environments demonstrate that our method surpasses existing zero-shot methods
  and achieves better cross-domain performance than supervised methods. Implementations
  are available at https://github.com/JunhaoXing/ZeroPlantSeg.
links:
- name: URL
  url: https://doi.org/10.1109/WACV61042.2026.00247
---
