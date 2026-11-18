---
title: Exploring the Latent Structure of AMD Severity Using Retinal Foundation Models
authors:
- Niccolò Fineschi
- Jovana Panic
- Atsushi Watanabe
- Hideaki Hayashi
- Kazuya Nishimura
- Yuki Maeno
- Samanta Rosati
- Gabriella Balestra
- Kohji Nishida
- Hajime Nagahara
date: '2026-09-01'
publishDate: '2026-11-18T01:25:31.776619Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE-EMBS International Conference on Biomedical
  and Health Informatics (BHI)*'
abstract: Retinal foundation models have demonstrated strong performance across a
  wide range of ophthalmic tasks, yet relatively little is known about how disease-related
  information is represented within their learned embeddings and whether this distribution
  influences downstream prediction performance. In this work, we use Age-related Macular
  Degeneration (AMD) as a case study to investigate how disease severity is represented
  within the embedding space of RET-CLIP, a retinal vision-language foundation model,
  using bilateral fundus images from the AREDS dataset, benchmarked against non-retinal
  encoders. We first characterize the distribution of AMD severity within the learned
  representation space and then evaluate how this structure influences classification
  performance across three clinically relevant task formulations of increasing granularity.
  Finally, we analyze the most influential latent dimensions combining feature attribution,
  statistical phenotype association, and qualitative image analyses. Our results show
  that RET-CLIP represents AMD severity as a continuous spectrum rather than a set
  of discrete categories, with healthy and advanced disease stages exhibiting clearer
  separation than intermediate ones. This organization was reflected in downstream
  performance, which decreased from a balanced accuracy of 0.844 and 0.814 for binary
  AMD and Late-AMD detection respectively to 0.446 for six-class grading. Furthermore,
  the most influential latent dimensions were statistically associated to distinct
  retinal phenotypes, including drusen accumulation, pigmentary alterations, and advanced
  retinal lesions. These findings suggest that the structure of retinal foundation-model
  representations influences the difficulty of clinically relevant prediction tasks
  and demonstrate the potential of representation-level analysis for understanding
  disease organization and improving interpretability.
links:
- name: URL
  url: https://arxiv.org/abs/2610.14138
---
