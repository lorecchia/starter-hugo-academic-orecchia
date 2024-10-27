---
title: "Training Binary Neural Networks via Gaussian Variational Inference and Low-Rank Semidefinite Programming" 
authors: 
- Lorenzo Orecchia
- Jiawei Hu
- Xue He
- Wang Zhe Mark
- Xulei Yang
- Min Wu
- Xue Geng
date: 2024-11-12
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Neural Information Processing Systems"
publication_short: "NeurIPS"

abstract: "Current methods for training Binarized Neural Networks (BNNs) heavily rely on the heuristic straight-through estimator (STE), which crucially enables the application of SGD-based optimizers to the combinatorial training problem. Although the STE heuristics and their variants have led to significant improvements in BNN performance, their theoretical underpinnings remain unclear and relatively understudied. In this paper, we propose a theoretically motivated optimization framework for BNN training based on Gaussian variational inference. In its simplest form, our approach yields a non-convex linear programming formulation whose variables and associated gradients motivate the use of latent weights and STE gradients. More importantly, our framework allows us to formulate semidefinite programming (SDP) relaxations to the BNN training task. Such formulations are able to explicitly models pairwise correlations between weights during training, leading to a more accurate optimization characterization of the training problem. As the size of such formulations grows quadratically in the number of weights, quickly becoming intractable for large networks, we apply the Burer-Monteiro approach and only optimize over linear-size low-rank SDP solutions. Our empirical evaluation on CIFAR-10, CIFAR-100, Tiny-ImageNet and ImageNet datasets shows our method consistently outperforming all state-of-the-art algorithms for training BNNs."

# Summary. An optional shortened abstract.
summary: 
tags:
- "neural network training"
- "semidefinite programming"
- "first-order methods"
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: NeurIPS Poster
  url: https://neurips.cc/virtual/2024/poster/94427


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
#image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
