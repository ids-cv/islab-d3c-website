---
title: Single-Image Depth From Defocus With Coded Aperture and Diffusion Posterior
  Sampling
authors:
- Hodaka Kawachi
- José Reinaldo Cunha Santos A. V. Silva Neto
- Yasushi Yagi
- Hajime Nagahara
- Tomoya Nakamura
date: '2026-01-01'
publishDate: '2026-11-18T01:25:30.061490Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Computational Imaging*'
doi: 10.1109/tci.2026.3697618
abstract: We propose a single-snapshot coded-aperture depth-from-defocus (DFD) method
  that reconstructs RGBD by posterior-guided diffusion, combining a learned RGBD diffusion
  prior with a differentiable DFD forward model. Given a measurement, we approximately
  sample from the posterior induced by the forward model (data fidelity) and the diffusion
  prior, using a denoise–correct–renoise procedure that applies data-consistency updates
  in the denoised domain. Unlike U-Net–style regressors, our approach requires no
  paired defocus–RGBD training data and does not couple training to a specific camera
  configuration. Experiments on comprehensive simulations and a prototype camera show
  stable RGBD reconstructions across noise levels, outperforming U-Net baselines and
  a classical coded-aperture DFD method.Our implementation and experimental configuration
  will be released publicly upon publication.
links:
- name: URL
  url: https://doi.org/10.1109/tci.2026.3697618
---
