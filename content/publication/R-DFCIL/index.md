---
publication_types:
  - "1"
authors:
  - Qiankun Gao
  - admin
  - Bernard Ghanem
  - Jian Zhang
publication: European Conference on Computer Vision (ECCV), 2022
publication_short: ECCV 2022
draft: false
url_pdf: https://arxiv.org/pdf/2203.13104.pdf
title: "R-DFCIL: Relation-Guided Representation Learning for Data-Free Class Incremental Learning"
abstract: "Class-Incremental Learning(CIL) struggles with catastrophic forgetting when learning new knowledge, and Data-Free CIL (DFCIL) is even more challenging without access to the training data of previously learned classes. Though recent DFCIL works introduce techniques such as model inversion to synthesize data for previous classes, they fail to overcome forgetting due to the severe domain gap between the synthetic and real data. To address this issue, this paper proposes relation-guided representation learning (RRL) for DFCIL, dubbed R-DFCIL. In RRL, we introduce relational knowledge distillation to flexibly transfer the structural relation of new data from the old model to the current model. Our RRL-boosted DFCIL can guide the current model to learn representations of new classes better compatible with representations of previous classes, which greatly reduces forgetting while improving plasticity. To avoid the mutual interference between representation and classifier learning, we employ local rather than global classification loss during RRL. After RRL, the classification head is refined with global class-balanced classification loss to address the data imbalance issue as well as learn the decision boundaries between new and previous classes. Extensive experiments on CIFAR100, Tiny-ImageNet200, and ImageNet100 demonstrate that our R-DFCIL significantly surpasses previous approaches and achieves a new state-of-the-art performance for DFCIL."
url_code: https://github.com/gqk/R-DFCIL
featured: true
date: 2022-07-01T18:27:40.971Z
---
