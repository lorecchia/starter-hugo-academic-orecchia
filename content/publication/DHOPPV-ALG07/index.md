---
title: "Localized Techniques for Broadcasting in Wireless Sensor Networks"
authors:
- Devdatt Dubhashi
- Olle Häggström
- Lorenzo Orecchia
- Alessandro Panconesi
- Chiara Petrioli
- Andrea Vitaletti
date: 2007-10-31
math: true


# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Algoroithmica"
publication_short: "Algorithmica"

abstract: "In this paper we tackle the problem of designing simple, localized, low energy consuming, reliable protocols for one-to-all communication in large scale wireless sensor networks. Our first proposed technique, called the Irrigator protocol, relies on the idea to first build a sparse overlay network, and then flood over it. The overlay network is set up by means of a simple, distributed, localized probabilistic protocol and spans all the sensor nodes with high probability. Based on the algorithmic ideas of the Irrigator protocol we then develop a second protocol, dubbed Fireworks, with similar performance that does not require any overlay network to be set up in advance. Asymptotic analytical results are provided which assess the reliability of the Irrigator and Fireworks techniques. The theoretical analysis of the proposed protocols is complemented and validated by a (simulation based) comparative performance evaluation that assesses several advantages of our new protocols with respect to gossiping and simple flooding. Differently from previous studies, we analyze and demonstrate the performance of our protocols for two different node distributions: The typical uniform distribution and a newly defined “hill” distribution, here introduced to capture some of the important and more realistic aspects of node deployment in heterogeneous terrain. Simulation results show that the proposed schemes achieve very good trade-offs between low overhead, low energy consumption and high reliability. In particular, the Irrigator and Fireworks protocols are more reliable than gossiping, and significantly reduce the number of links along which a message is sent over both flooding and gossiping."


# Summary. An optional shortened abstract.
summary: 
tags:
- "wireless sensor networks"
- "local algorithms"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Algorithmica
  url: https://link.springer.com/article/10.1007/s00453-007-9092-8

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
