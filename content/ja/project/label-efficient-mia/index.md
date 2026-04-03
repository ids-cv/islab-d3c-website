---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Label-efficient Medical Image Analysis"
summary: "半教師あり学習や弱教師あり学習などのLabel-efficient learningを活用し、少ないアノテーションコストで高精度な医用画像解析を実現する手法の研究に取り組んでいます。"
authors: ["Kazuya Nishimura"]
tags: ["Medical Image Analysis", "Deep Learning", "Label-efficient Learning"]
categories: []
date: 2026-04-03T00:00:00+09:00

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

本研究室では、病理画像、顕微鏡画像、眼底画像、内視鏡画像などの疾患の診断や治療のために取得された医療画像に着目し、これらの画像から機械学習技術を用いて、病変位置の特定や疾患の種類の分類を目標とした医用画像解析の研究に取り組んでいます。深層学習の登場により認識技術は急速に発展し、十分な学習データがあれば高精度な解析が実現可能となりつつあります。

一方で、医用画像解析には大きな課題があります。それは、高品質な教師データ（アノテーション）を大量に用意することが難しいという点です。医用画像のラベル付けは医師や専門家によって行われる必要があり、多大な時間と労力を要します。例えば、病理画像では腫瘍領域をピクセル単位で正確に指定する必要があり、細胞レベルのアノテーションには専門的な知識と長時間の作業が必要になります。

このような背景から、本研究室では少ないラベルで高精度な解析を実現する**Label-efficient learning**に取り組んでいます。具体的には、少量の教師データと大量の未ラベルデータを活用する半教師あり学習（semi-supervised learning）や、粗いラベルから学習を行う弱教師あり学習（weakly supervised learning）などの手法を開発し、医用画像解析への応用を進めています。これにより、アノテーションコストを大幅に削減しながら、実際の医療現場で利用可能な医用画像解析技術の実現を目指しています。
