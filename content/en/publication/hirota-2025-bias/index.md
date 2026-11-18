---
title: 'Bias in Gender Bias Benchmarks: How Spurious Features Distort Evaluation'
authors:
- Yusuke Hirota
- Ryo Hachiuma
- Bo-Yi Li
- Ximing Lu
- Michael Boone
- Boris Ivanovic
- Yejin Choi
- Marco Pavone
- Yu-Chiang Frank Wang
- Noa Garcia
- Yuta Nakashima
- Chao-Han Huck Yang
date: '2025-10-01'
publishDate: '2026-11-18T01:25:30.102610Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF International Conference on Computer Vision
  (ICCV)*'
doi: 10.1109/ICCV51701.2025.00808
abstract: 'Gender bias in vision-language foundation models (VLMs) raises concerns
  about their safe deployment and is typically evaluated using benchmarks with gender
  annotations on real-world images. However, as these benchmarks often contain spurious
  correlations between gender and non-gender features, such as objects and backgrounds,
  we identify a critical oversight in gender bias evaluation: Do spurious features
  distort gender bias evaluation? To address this question, we systematically perturb
  non-gender features across four widely used benchmarks (COCO-gender, FACET, MIAP,
  and PHASE) and various VLMs to quantify their impact on bias evaluation. Our findings
  reveal that even minimal perturbations, such as masking just 10 % of objects or
  weakly blurring backgrounds, can dramatically alter bias scores, shifting metrics
  by up to 175 % in generative VLMs and 43 % in CLIP variants. This suggests that
  current bias evaluations often reflect model responses to spurious features rather
  than gender bias, undermining their reliability. Since creating spurious feature-free
  benchmarks is fundamentally challenging, we recommend reporting bias metrics alongside
  feature-sensitivity measurements to enable a more reliable bias assessment.'
links:
- name: URL
  url: https://doi.org/10.1109/ICCV51701.2025.00808
---
