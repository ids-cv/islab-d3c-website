---
title: 'Interaction-via-Actions: Cattle Interaction Detection with Joint Learning
  of Action-Interaction Latent Space'
authors:
- Ren Nakagawa
- Yang Yang
- Risa Shinoda
- Hiroaki Santo
- Kenji Oyama
- Fumio Okura
- Takenao Ohkawa
date: '2026-03-01'
publishDate: '2026-11-18T01:25:30.045296Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Winter Conference on Applications of Computer
  Vision (WACV)*'
doi: 10.1109/WACV61042.2026.00197
abstract: This paper introduces a method and application for automatically detecting
  behavioral interactions between grazing cattle from a single image, which is essential
  for smart livestock management in the cattle industry, such as for detecting estrus.
  Although interaction detection for humans has been actively studied, a non-trivial
  challenge lies in cattle interaction detection, specifically the lack of a comprehensive
  behavioral dataset that includes interactions, as the interactions of grazing cattle
  are rare events. We, therefore, propose CattleAct, a data-efficient method for interaction
  detection by decomposing interactions into the combinations of actions by individual
  cattle. Specifically, we first learn an action latent space from a large-scale cattle
  action dataset. Then, we embed rare interactions via the fine-tuning of the pre-trained
  latent space using contrastive learning, thereby constructing a unified latent space
  of actions and interactions. On top of the proposed method, we develop a practical
  working system integrating video and GPS inputs. Experiments on a commercial-scale
  pasture demonstrate the accurate interaction detection achieved by our method compared
  to the baselines. Our implementation is available at https://github.com/rakawanegan/CattleAct.
links:
- name: URL
  url: https://doi.org/10.1109/WACV61042.2026.00197
---
