---
title: "Flow-Based Algorithms for Local Graph Clustering"
authors:
- Zeyuan Allen-Zhu
- Lorenzo Orecchia
date: "2013-07-10T00:00:00Z"
math: true


# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 25th Annual ACM-SIAM Symposium on Discrete Algorithms"
publication_short: "SODA"

abstract: "Given a subset S of vertices of an undirected graph G, the cut-improvement problem asks us to find a subset S that is similar to A but has smaller conductance. A 
very elegant algorithm for this problem has been given by Andersen and Lang [AL08] and requires solving a small number of single-commodity maximum flow computations over the whole graph G. In this paper, we introduce LocalImprove, the first cut-improvement algorithm that is local, i.e. that runs in time dependent on the size of the input set A rather than on the size of the entire graph. Moreover, LocalImprove achieves this local behaviour while essentially matching the same theoretical guarantee as the global algorithm of Andersen and Lang.
The main application of LocalImprove is to the design of better local-graph-partitioning algorithms. All previously known local algorithms for graph partitioning are random-walk based and can only guarantee an output conductance of $O(\sqrt{OPT})$ when the target set has conductance $OPT \in [0,1].$ Very recently, Zhu, Lattanzi and Mirrokni [ZLM13] improved this to $O(OPT / \sqrt{CONN})$ where the internal connectivity parameter $CONN \in [0,1]$ is defined as the reciprocal of the mixing time of the random walk over the graph induced by the target set. In this work, we show how to use LocalImprove to obtain a constant approximation O(OPT) as long as $CONN/OPT = Omega(1).$ This yields the first flow-based algorithm. Moreover, its performance strictly outperforms the ones based on random walks and surprisingly matches that of the best known global algorithm, which is SDP-based, in this parameter regime [MMV12].
Finally, our results show that spectral methods are not the only viable approach to the construction of local graph partitioning algorithm and open door to the study of algorithms with even better approximation and locality guarantees."


# Summary. An optional shortened abstract.
summary: 
tags:
- "graph partitioning"
- "network flows"
- "local algorithms"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: http://arxiv.org/abs/1307.2855
- name: SIAM
  url: http://epubs.siam.org/doi/pdf/10.1137/1.9781611973402.94
url_preprint: 
url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
