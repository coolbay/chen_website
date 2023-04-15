---
title: "ThumbNet: One Thumbnail Image Contains All You Need for Recognition"
publication_types:
  - "1"
authors:
  - admin
  - Bernard Ghanem
publication_short: ACM MM'20
abstract: Although deep convolutional neural networks (CNNs) have achieved great
  success in computer vision tasks, its real-world application is still impeded
  by its voracious demand of computational resources. Current works mostly seek
  to compress the network by reducing its parameters or parameter-incurred
  computation, neglecting the influence of the input image on the system
  complexity. Based on the fact that input images of a CNN contain substantial
  redundancy, in this paper, we propose a unified framework, dubbed as
  ThumbNet,  to simultaneously accelerate and compress CNN models by enabling
  them to infer on one thumbnail image. We provide three effective strategies to
  train ThumbNet. In doing so, ThumbNet learns an inference network that
  performs equally well on small images as the original-input network on large
  images. With ThumbNet, not only do we obtain the thumbnail-input inference
  network that can drastically reduce computation and memory requirements, but
  also we obtain an image downscaler that can generate thumbnail images for
  generic classification tasks. Extensive experiments show the effectiveness of
  ThumbNet, and demonstrate that the thumbnail-input inference network learned
  by ThumbNet can adequately retain the accuracy of the original-input network
  even when the input images are downscaled 16 times.
draft: false
featured: false
tags:
  - Deep learning
  - network acceleration
  - image classification
  - auto-encoder
  - knowledge distillation
slides: ""
url_pdf: https://arxiv.org/pdf/1904.05034.pdf
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
summary: "Tackle the problem of network compression and acceleration in a novel
  perspective: enabling inference on thumbnail images without compromising
  accuracy. Propose supervised image downscaling, distillation-boosted
  supervision and feature-mapping regularization."
url_dataset: ""
url_project: ""
url_source: ""
url_video: https://www.youtube.com/watch?v=m0Ms0xtSKFI&list=PLC28kDljnOrj-_w-MHKW36gVRvUe3XFjx
author_notes: []
doi: ""
publication: ACM International Conference on Multimedia, Seattle, United State,  2020
projects: []
date: 2020-07-29T00:00:02.020Z
url_slides: ""
publishDate: 2020
url_poster: ""
url_code: ""
---
