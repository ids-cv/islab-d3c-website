---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Label-efficient Medical Image Analysis"
summary: "We develop label-efficient learning methods—including semi-supervised and weakly supervised learning—to achieve high-accuracy medical image analysis with limited annotated data, reducing the burden of expert annotation in clinical settings."
authors: ["Kazuya Nishimura"]
tags: ["Medical Image Analysis", "Deep Learning", "Label-efficient Learning"]
categories: []
date: 2026-04-02T00:00:00+09:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
 caption: ""
 focal_point: ""
 preview_only: True

# Custom links (optional).
# Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
# url: https://twitter.com
# icon_pack: fab
# icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
# Associate this project with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# Otherwise, set `slides = ""`.
slides: ""
---

## Label-efficient Medical Image Analysis

We focus on medical images acquired for disease diagnosis and treatment—such as pathological images, microscopic images, fundus images, and endoscopic images—and conduct research on medical image analysis aimed at identifying lesion locations and classifying disease types using machine learning techniques.

With the advent of deep learning, recognition technologies have rapidly advanced, and high-accuracy analysis is becoming achievable when sufficient training data is available.

However, there is a major challenge in medical image analysis: it is difficult to prepare a large amount of high-quality labeled data (annotations). Labeling medical images must be performed by physicians or specialists, requiring substantial time and effort. For example, for pathological images, tumor regions must be precisely annotated at the pixel level, and cell-level annotation requires expert knowledge and long hours of work.

Against this background, our laboratory is working on label-efficient learning, which aims to achieve high-accuracy analysis with limited labeled data. Specifically, we develop methods such as semi-supervised learning, which leverages a small amount of labeled data together with a large amount of unlabeled data, and weakly supervised learning, which learns from coarse labels, and apply them to medical image analysis. Through these approaches, we aim to significantly reduce annotation costs while developing medical image analysis technologies that can be used in real clinical settings.
