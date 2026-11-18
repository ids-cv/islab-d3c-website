---
title: A single-camera video-based assessment of locomotive syndrome using pose-silhouette
  fusion model
authors:
- Yu Moriguchi
- Junichi Kushioka
- Noriko Takemura
- Hiroki Hagizawa
- Masafumi Kashii
- Ichiro Nakahara
- Taichi Kimura
- Keisuke Akiyama
- Taku Fujimoto
- Hajime Nagahara
- Keiko Yamada
- Rodrigo Navarro-Ramirez
- Takenori Oda
- Hideki Mochizuki
- Ken Nakata
- Seiji Okada
- Satoru Tada
date: '2026-06-01'
publishDate: '2026-11-18T01:25:31.796997Z'
publication_types:
- article-journal
publication: '*PLOS Digital Health*'
doi: 10.1371/journal.pdig.0001530
abstract: Locomotive syndrome (LS), characterized by declining mobility due to musculoskeletal
  disorders, significantly affects older adults and is highly prevalent in Japan.
  Early detection and intervention are crucial to mitigate disease progression and
  preserve quality of life. Current diagnostic methods rely on subjective self-reports
  and labor-intensive clinical assessments, underscoring the need for automated, objective,
  and scalable screening tools. Building on our previous work, this study presents
  an updated deep learning-based computer vision model for LS screening using single-camera
  walking videos. We collected 511 walking videos from 178 participants clinically
  classified into four LS stages (non-LS, stage 1, stage 2, and stage 3). We used
  the MMPose framework to extract 2D body keypoints and generated silhouette-based
  Gait Energy Images (GEIs) from seven frames automatically sampled from fixed 40-frame
  walking windows to capture complementary gait-shape information. Model performance
  was evaluated using 10-fold cross-validation based on held-out evaluation-window
  predictions, while ensuring that windows from the same participant and the same
  walking video were not split across training, validation, and test sets. We also
  evaluated an independent external validation cohort of 33 cases (LS0–1, n = 15;
  LS2–3, n = 18). In internal validation, the pose-estimation model achieved sensitivity
  of 0.9440 and an AUC of 0.9668, whereas the silhouette model showed specificity
  of 0.9085 and an AUC of 0.9191. Fusion models outperformed the individual approaches,
  with the highest F1-score (0.908) at a 60:40 pose-to-silhouette ratio and the highest
  AUC (0.971) at a 70:30 ratio. In external validation, the score-fusion model achieved
  90.9% accuracy, 88.9% sensitivity, 93.3% specificity, a macro-F1 score of 0.909,
  and an AUC of 0.967. In conclusion, integrating pose-estimation and silhouette-based
  features substantially improves the accuracy and clinical utility of automated LS
  screening. This low-burden approach provides a practical bridge between population-level
  screening and definitive clinical assessment.
links:
- name: URL
  url: https://doi.org/10.1371/journal.pdig.0001530
---
