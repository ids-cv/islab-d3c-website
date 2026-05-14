+++
date = 2026-04-20
title = "Vision and Omics"

draft = true
toc = true # Show table of contents? true/false
type = "book" # Do not modify.
weight = 50

[menu.topics]
 weight = 50
+++

In the fields of medicine and life sciences, large volumes of "image data," such as microscopy and medical imaging, and "omics data," including genomics, transcriptomics, and proteomics, have been rapidly accumulating. Although these data provide complementary perspectives on the same biological phenomena, they are often analyzed independently, limiting a comprehensive and integrated understanding.

In particular, linking morphological characteristics of cells and tissues (images) with molecular-level changes (omics) is expected to greatly contribute to elucidating disease mechanisms and advancing diagnostics and therapeutic strategies. However, due to differences in data formats and scales, as well as fragmentation in analytical methodologies, a robust framework for their integrated analysis has yet to be fully established.

## Gene Expression Estimation

Estimating gene expression from pathology images has the potential to significantly reduce the cost and effort of RNA sequencing. Conventional approaches relied on point-wise loss functions to predict absolute expression values; however, such values were often corrupted by stochastic noise and batch effects inherent in sequencing processes.
To address this challenge, we focused on learning relative expression patterns rather than absolute levels. We proposed a novel loss function, STRank, which modeled gene-wise relationships under the assumption that relative expression patterns remain consistent across experiments. This formulation improved robustness against noise and batch effects, leading to more reliable gene expression estimation from images.

{{< figure library="true" src="vision_omics_1.png" title="(a) Illustration of scaling bias due to batch effects, (b) stochastic noise, and (c) our hypothesis: learning relative expression trends. Even in the presence of batch effects and stochastic noise, the relative expression trends between patches are preserved." numbered="true" >}}

## Multi-modal Integration

Integrating pathology images with gene expression data enables scalable and cost-effective molecular profiling with strong clinical relevance. Existing methods typically treated gene expression as a coarse slide- or spot-level signal, overlooking its underlying cell-level structure.
We proposed a Cell-type Prototype-informed Neural Network (CPNN) that incorporated prior knowledge from single-cell RNA sequencing data. By estimating cell-type prototypes that captured stable gene–gene relationships, the model learned cell-type compositions directly from images and linked them to observed expression profiles. This approach improved prediction accuracy across multiple datasets and provided interpretable insights into the cellular composition driving gene expression.

{{< figure library="true" src="vision_omics_2.png" title="Illustration of concept of Cell-type Prototype-informed Neural Network (CPNN). We estimate gene expression based on cell-type prototypes by modeling the relationship between observed gene expression and cell-level gene expression." numbered="true" >}}

## Representation Learning

Spatial transcriptomics (ST) provides spatially resolved gene expression alongside pathology images, offering a rich source of supervision for image understanding. However, strong batch effects across experiments hindered the extraction of consistent biological signals.
We proposed a batch-agnostic contrastive learning framework that leveraged ST data to learn robust image representations. By introducing a variationally trained gene encoder, the method extracted consistent gene expression signals across patients and used them to guide representation learning. This enabled improved performance in downstream tasks such as pathological image classification while mitigating batch-related variability.

{{< figure library="true" src="vision_omics_3.png" title="Overview of our method. scVI or scANVI are trained with the gene expression, and the encoder is reused for contrastive learning." numbered="true" >}}
