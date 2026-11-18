---
title: Automated acquisition of thyroid cytology image features using self-supervised
  learning and application to image classification
authors:
- Masatoshi Abe
- Ayana Suzuki
- Kumiko Kamada
- Toshiya Kanno
- Mayu Shimasaki
- Toshinori Mori
- Hajime Nagahara
- Akira Miyauchi
- Takashi Akamizu
- Mitsuyoshi Hirokawa
- Hirohiko Niioka
date: '2026-10-01'
publishDate: '2026-11-18T01:25:29.937656Z'
publication_types:
- article-journal
publication: '*Communications Medicine*'
doi: 10.1038/s43856-026-01874-2
abstract: Thyroid fine-needle aspiration cytology is widely used to evaluate thyroid
  nodules before surgery. Recent advances in deep learning have increased the potential
  for artificial intelligence-assisted cytological diagnosis. However, developing
  accurate models usually requires large numbers of images labelled by experts, making
  dataset preparation time-consuming and costly. We investigate whether self-supervised
  learning can improve thyroid cytology image classification while reducing the need
  for labelled data. We retrospectively analysed cytology images from 393 thyroid
  nodules and extracted 142,158 image patches. Three self-supervised learning methods
  were used to pre-train vision transformer models on unlabelled images, followed
  by classification training with different amounts of labelled data. Performance
  in classifying eight lesion types was assessed using five-fold cross-validation,
  precision–recall area under the curve, and macro-averaged F1 scores. Model performance
  was compared with ImageNet-pretrained models and four cytotechnologists. Here we
  show that self-supervised learning maintains high classification performance when
  labelled training data are limited and consistently outperforms ImageNet pre-training.
  With 1% of the labelled data, the best self-supervised model achieves a precision–recall
  area under the curve of 0.899, compared with 0.707 for ImageNet pre-training. The
  diagnostic pipeline achieves an average class-specific accuracy of 0.94, exceeding
  that of the four participating cytotechnologists. Self-supervised image representations
  also form lesion-specific clusters without diagnostic labels. Self-supervised learning
  enables accurate classification of thyroid cytology images while substantially reducing
  the need for expert annotation. This approach may facilitate the development of
  more efficient artificial intelligence-assisted cytology systems, although validation
  using data from multiple institutions is needed.
links:
- name: URL
  url: https://doi.org/10.1038/s43856-026-01874-2
---
