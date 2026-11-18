---
title: Semantic Segmentation for Pixel-Wise Visualization of Breast Cancer in Deep
  Ultraviolet-Excited Fluorescence Images
authors:
- Tomoya Matsui
- Ryuta Nakao
- Shunsuke Tomimoto
- Junya Sato
- Hirohiko Niioka
- Ippei Takada
- Yoshinori Harada
- Hideo Tanaka
- Eiichi Konishi
- Hajime Nagahara
- Midori Morita
- Yasuto Naoi
- Tetsuya Taguchi
- Tetsuro Takamatsu
date: '2026-04-01'
publishDate: '2026-11-18T01:25:30.019720Z'
publication_types:
- article-journal
publication: '*Acta Histochemica et Cytochemica*'
doi: 10.1267/ahc.26-00007
abstract: Microscopy with ultraviolet surface excitation (MUSE) enables rapid fluorescence
  imaging of tissue surfaces, but MUSE images differ markedly from conventional hematoxylin
  and eosin images, making cancer delineation challenging for routine pathological
  practice. We investigated the feasibility of deep learning-based semantic segmentation,
  which assigns a class label to each pixel, for pixel-wise breast cancer detection
  in MUSE images. Fresh breast tissues from 30 mastectomy patients with breast cancer
  were stained with terbium and Hoechst and imaged by MUSE. A total of 150 cancerous
  images (five per case) were manually annotated into cancerous and non-cancerous
  classes, and 300 non-cancerous images (ten per case) were collected. Models were
  trained and evaluated using five-fold nested cross-validation, comparing a cancer-only
  (CO) model trained solely on cancerous images with a cancer plus non-cancer (CN)
  model trained on both cancerous and non-cancerous images. The CO model achieved
  a higher Dice score than the CN model (CO, 0.7478; CN, 0.7343). Sliding window-based
  majority voting post-processing reduced scattered false-positive areas and improved
  Dice scores (CO, 0.7984; CN, 0.7849). These results support the feasibility of deep
  learning-based semantic segmentation for visualizing breast cancer regions and provide
  a basis for future quantitative applications using MUSE images.
links:
- name: URL
  url: https://doi.org/10.1267/ahc.26-00007
---
