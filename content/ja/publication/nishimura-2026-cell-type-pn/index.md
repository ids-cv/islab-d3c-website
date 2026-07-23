---
title: Cell-Type Prototype-Informed Neural Network for Gene Expression Estimation
  from Pathology Images
authors:
- Kazuya Nishimura
- Ryoma Bise
- Shinnosuke Matsuo
- Haruka Hirose
- Yasuhiro Kojima
date: '2026-01-01'
publishDate: '2026-07-23T03:38:49.340961Z'
publication_types:
- paper-conference
publication: '*Proc. IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
abstract: Estimating slide- and patch-level gene expression profiles from pathology
  images enables rapid and low-cost molecular analysis with broad clinical impact.
  Despite strong results, existing approaches treat gene expression as a mere slide-
  or spot-level signal and do not incorporate the fact that the measured expression
  arises from the aggregation of underlying cell-level expression. To explicitly introduce
  this missing cell-resolved guidance, we propose a Cell-type Prototype-informed Neural
  Network (CPNN) that leverages publicly available single-cell RNA-sequencing datasets.
  Since single-cell measurements are noisy and not paired with histology images, we
  first estimate cell-type prototypes-mean expression profiles that reflect stable
  gene-gene co-variation patterns. CPNN then learns cell-type compositional weights
  directly from images and models the relationship between prototypes and observed
  bulk or spatial expression, providing a biologically grounded and structurally regularized
  prediction framework. We evaluate CPNN on three slide-level datasets and three patch-level
  spatial transcriptomics datasets. Across all settings, CPNN achieves the highest
  performance in terms of Spearman correlation. Moreover, by visualizing the inferred
  compositional weights, our framework provides interpretable insights into which
  cell types drive the predicted expression. Code is publicly available at https://github.com/naivete5656/CPNN.
---
