---
title: Unsupervised Confidence Calibration for Active Learning
authors:
- Naoya Fukui
- Hideaki Hayashi
- Hajime Nagahara
date: '2026-04-01'
publishDate: '2026-07-23T03:38:47.249940Z'
publication_types:
- paper-conference
publication: '*Proceedings of IEEE International Symposium on Biomedical Imaging (ISBI)*'
doi: 10.1109/ISBI61048.2026.11515622
abstract: In active learning, training data to be annotated is generally selected
  based on the confidence scores output by a classifier. However, the selection of
  the initial training data pool typically relies on random sampling since the classifier
  has not yet been trained. To address this issue, it is necessary to obtain a classifier
  that can appropriately assess confidence without supervised learning at the initial
  pool selection stage. In this study, we propose an unsupervised confidence calibration
  method based on domain adaptation. The proposed framework integrates a variational
  autoencoder into an unsupervised domain adaptation method and trains them simultaneously,
  thereby allowing the estimation of the joint distribution of input data and class
  labels. The proposed framework enables the classifier to compute reliable confidence
  scores for the target domain in a completely unsupervised manner. We conducted experiments
  on medical image datasets to evaluate the effectiveness of the proposed unsupervised
  confidence calibration method and its impact on active learning. Experimental results
  showed that the proposed method consistently outperforms the baseline in all six
  transfer settings, achieving an average improvement of 1.0--1.5 points in classification
  accuracy across domains.
links:
- name: URL
  url: https://doi.org/10.1109/ISBI61048.2026.11515622
---
