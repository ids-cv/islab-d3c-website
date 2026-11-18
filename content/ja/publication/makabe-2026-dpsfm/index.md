---
title: 'DP-SfM: Dual-Pixel Structure-From-Motion Without Scale Ambiguity'
authors:
- Lilika Makabe
- Kohei Ashida
- Hiroaki Santo
- Fumio Okura
- Yasuyuki Matsushita
date: '2026-05-01'
publishDate: '2026-11-18T01:25:31.834462Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence*'
doi: 10.1109/tpami.2026.3690655
abstract: Multi-view 3D reconstruction, namely, structure-from-motion followed by
  multi-view stereo, is a fundamental component of 3D computer vision. In general,
  multi-view 3D reconstruction suffers from an unknown scale ambiguity unless a reference
  object of known size is present in the scene. In this article, we show that multi-view
  images captured using a dual-pixel (DP) sensor can automatically resolve the scale
  ambiguity, without requiring a reference object or prior calibration. Specifically,
  the defocus blur observed in DP images provides sufficient information to determine
  the absolute scale when paired with depth maps (up to scale) recovered from multi-view
  3D reconstruction. Based on this observation, we develop a simple yet effective
  linear method to estimate the absolute scale, followed by the intensity-based optimization
  stage that aligns the left and right DP images by shifting them back toward each
  other using cross-view blur kernels. Experiments demonstrate the effectiveness of
  the proposed approach across diverse scenes captured with different cameras and
  lenses.
links:
- name: URL
  url: https://doi.org/10.1109/tpami.2026.3690655
---
