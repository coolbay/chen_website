---
publication_types:
  - "1"
authors:
  - Mengmeng Xu
  - admin
  - David Rojas Blanco
  - Ali Thabet
  - Bernard Ghanem
publication: IEEE Conference on Computer Vision and Pattern Recognition,
  Seattle, United State, 2020
publication_short: CVPR'20
abstract: "Temporal action detection is a fundamental yet challenging task in
  video understanding. Video context is a critical cue to effectively detect
  actions, but current works mainly focus on temporal context, while neglecting
  semantic context as well as other important context properties. In this work,
  we propose a graph convolutional network (GCN) model to adaptively
  incorporate  multi-level semantic context into video features and cast
  temporal action detection as a sub-graph localization problem. Specifically,
  we formulate video snippets as graph nodes, snippet-snippet correlations as
  edges, and actions associated with context as target sub-graphs. With graph
  convolution as the basic operation, we design a GCN block called GCNeXt, which
  learns the features of each node by aggregating its context and dynamically
  updates the edges in the graph. To localize each sub-graph, we also design an
  SGAlign layer to embed each sub-graph into the Euclidean space. Extensive
  experiments show that G-TAD is capable of finding effective video context
  without extra supervision and achieves state-of-the-art performance on two
  detection benchmarks. On ActivityNet-1.3, it obtains an average mAP of 34.09%;
  on THUMOS14, it reaches 51.6% at IoU@0.5 when combined with a proposal
  processing method. "
draft: false
url_pdf: https://arxiv.org/pdf/1911.11462.pdf
url_project: https://www.deepgcns.org/app/g-tad
url_video: https://www.youtube.com/watch?v=BlPxnDcykUo
title: "G‑TAD: Sub‑Graph Localization for Temporal Action Detection"
featured: false
date: 2020-02-27T18:27:40.971Z
url_slides: https://www.slideshare.net/MengmengXu3/gtad-subgraph-localization-for-temporal-action-detection
image:
  filename: featured.png
  focal_point: ""
  preview_only: false
url_code: https://github.com/Frostinassiky/gtad
---
