---
title: Flash LiDAR system using charge-domain time-compressive ToF CMOS image sensor
  and deep learning
authors:
- Daisuke Hayashi
- Michitaka Yoshida
- De Xing Lioe
- Keita Yasutomi
- Shoji Kawahito
- Hajime Nagahara
- Keiichiro Kagawa
date: '2025-03-01'
publishDate: '2026-11-18T01:25:30.175504Z'
publication_types:
- paper-conference
publication: '*Proceedings of Photonic Instrumentation Engineering XII*'
doi: 10.1117/12.3040445
abstract: We have proposed a LiDAR system that compresses the scene response in the
  charge domain using a compressive CMOS image sensor based on the indirect time-of-flight
  (i-ToF) image sensor. The accuracy of depth estimation can be improved by considering
  multipath interference (MPI) caused by multiple reflections and scattering of light
  in the ToF depth imaging. The direct ToF (d-ToF) method is less affected by MPI
  because it measures the scene response directly using single-photon avalanche diodes
  (SPADs). However, it is costly to implement d-ToF image sensors and difficult to
  achieve high pixel counts. In our multi-tap i-ToF image sensor, a compressed scene
  response is acquired at each pixel and the scene response is restored by ADMM-Net.
  It is processed by U-Net to estimate the MPI-corrected depth image. In the experiment,
  we illuminated objects through a diffusive sheet with a pulsed light source (wavelength
  660nm, pulse width of 2.5ns FWHM) and captured the reflected light with our prototype
  sensor with 212 x 188 pixels operated at 606MHz with 32-bit exposure codes. The
  depth obtained by peak detection for the restored transient images exhibited the
  objects and the diffusive sheet separately.
links:
- name: URL
  url: https://doi.org/10.1117/12.3040445
---
