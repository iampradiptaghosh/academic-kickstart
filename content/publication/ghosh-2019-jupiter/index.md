---
title: "Jupiter: A Networked Computing Architecture"
date: 2019-01-01
publishDate: 2020-07-05T17:44:09.681935Z
authors: ["Pradipta Ghosh", "Quynh Nguyen", "Pranav K Sakulkar", "Jason A Tran", "Aleksandra Knezevic", "Jiatong Wang", "Zhifeng Lin", "Bhaskar Krishnamachari", "Murali Annavaram", "Salman Avestimehr"]

publication_types: ["1"]
abstract: "Modern latency-sensitive applications such as real-time multi-camera
  video analytics require networked computing to meet the time constraints. We present Jupiter, an open-source networked computing system that inputs a Directed Acyclic Graph (DAG)-based computational task graph to efficiently distribute the tasks among a set of networked compute nodes and orchestrates the execution thereafter. This Kubernetes container-orchestration-based system includes a range of profilers: network profilers, resource profilers, and execution time profilers; to support both centralized and decentralized scheduling algorithms. While centralized scheduling algorithms with global knowledge have been popular among the grid/cloud computing community, we argue that a distributed scheduling approach is better suited for networked computing due to lower communication and computation overhead in the face of network dynamics. We propose a new class of distributed scheduling algorithms called WAVE and show that despite using more localized knowledge, the WAVE algorithm can match the performance of a well-known centralized scheduling algorithm called Heterogeneous Earliest Finish Time (HEFT). To this, we present a set of real-world experiments on two separate testbeds: (1) a worldwide network of 90 cloud computers across eight cities and (2) a cluster of 30 Raspberry pi nodes."
featured: false
publication: "*UCC ’21 Companion*, December 6–9, 2021, Leicester, United Kingdom"# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/pdf/10.1145/3492323.3495630
url_code:
url_dataset: https://github.com/ANRGUSC/Jupiter
url_poster:
url_project: "project/dcp/"
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["dcp"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


