---
title: 'NeuraLeaf: Neural Parametric Leaf Models with Shape and Deformation Disentanglement'
authors:
- Yang Yang
- Dongni Mao
- Hiroaki Santo
- Yasuyuki Matsushita
- Fumio Okura
date: '2025-10-01'
publishDate: '2026-11-18T01:25:31.925870Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF International Conference on Computer Vision
  (ICCV)*'
doi: 10.1109/ICCV51701.2025.02615
abstract: We develop a neural parametric model for 3D leaves for plant modeling and
  reconstruction that are essential for agriculture and computer graphics. While neural
  parametric models are actively studied for humans and animals, plant leaves present
  unique challenges due to their diverse shapes and flexible deformation. To this
  problem, we introduce a neural parametric model for leaves, NeuraLeaf. Capitalizing
  on the fact that flattened leaf shapes can be approximated as a 2D plane, NeuraLeaf
  disentangles the leaves' geometry into their 2D base shapes and 3D deformations.
  This representation allows learning from rich sources of 2D leaf image datasets
  for the base shapes, and also has the advantage of simultaneously learning textures
  aligned with the geometry. To model the 3D deformation, we propose a novel skeleton-free
  skinning model and create a newly captured 3D leaf dataset called DeformLeaf. We
  show that NeuraLeaf successfully generates a wide range of leaf shapes with deformation,
  resulting in accurate model fitting to 3D observations like depth maps and point
  clouds. Our implementation and dataset are available at https://neuraleaf-yang.github.io/.
links:
- name: URL
  url: https://doi.org/10.1109/ICCV51701.2025.02615
---
