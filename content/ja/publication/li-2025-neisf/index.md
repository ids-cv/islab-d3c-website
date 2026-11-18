---
title: 'NeISF++: Neural Incident Stokes Field for Polarized Inverse Rendering of Conductors
  and Dielectrics'
authors:
- Chen-Hao Li
- Taishi Ono
- Takeshi Uemori
- Sho Nitta
- Hajime Mihara
- Alexander Gatto
- Hajime Nagahara
- Yusuke Moriuchi
date: '2025-01-01'
publishDate: '2026-11-18T01:25:32.021456Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition (CVPR)*'
doi: 10.1109/CVPR52734.2025.02467
abstract: Recent inverse rendering methods have improved shape, material, and illumination
  reconstruction using polarization cues. However, they only support dielectrics,
  ignoring conductors, which are common in everyday life. Since conductors and dielectrics
  have different reflection properties, using previous dielectrics-based methods will
  lead to obvious errors. In addition, conductors are glossy, which may cause strong
  specular reflection and is hard to reconstruct. To solve the above issues, we propose
  NeISF++, an inverse rendering pipeline that supports conductors and dielectrics.
  The key ingredient for our proposal is a general pBRDF that describes both conductors
  and dielectrics. As for the strong specular reflection problem, we propose a novel
  geometry initialization method using DoLP images. This physical cue is invariant
  to intensities and thus robust to strong specular reflections. Experimental results
  on our synthetic and real datasets show that our method surpasses the existing polarized
  inverse rendering methods for geometry and material decomposition as well as downstream
  tasks like relighting.
links:
- name: URL
  url: https://doi.org/10.1109/CVPR52734.2025.02467
---
