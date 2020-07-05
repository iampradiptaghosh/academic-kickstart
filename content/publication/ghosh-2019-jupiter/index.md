---
title: "Jupiter: A Networked Computing Architecture"
date: 2019-01-01
publishDate: 2020-07-05T17:44:09.681935Z
authors: ["Pradipta Ghosh", "Quynh Nguyen", "Pranav K Sakulkar", "Aleksandra Knezevic", "Jason A Tran", "Jiatong Wang", "Zhifeng Lin", "Bhaskar Krishnamachari", "Murali Annavaram", "Salman Avestimehr"]
publication_types: ["3"]
abstract: "In the era of Internet of Things, there is an increasing demand for networked computing to support the requirements of the time-constrained, compute-intensive distributed applications such as multi-camera video processing and data fusion for security. We present Jupiter, an open source networked computing system that inputs a Directed Acyclic Graph (DAG)-based computational task graph to efficiently distribute the tasks among a set of networked compute nodes regardless of their geographical separations and orchestrates the execution of the DAG thereafter. This Kubernetes container-orchestration-based system supports both centralized and decentralized scheduling algorithms for optimally mapping the tasks based on information from a range of profilers: network profilers, resource profilers, and execution time profilers. While centralized scheduling algorithms with global knowledge have been popular among the grid/cloud computing community, we argue that a distributed scheduling approach is better suited for networked computing due to lower communication and computation overhead in the face of network dynamics. To this end, we propose and implement a new class of distributed scheduling algorithms called WAVE on the Jupiter system. We present a set of real world experiments on two separate testbeds - one a world-wide network of 90 cloud computers across 8 cities and the other a cluster of 30 Raspberry pi nodes, over a simple networked computing application called Distributed Network Anomaly Detector (DNAD). We show that despite using more localized knowledge, a distributed WAVE greedy algorithm can achieve similar performance as a classical centralized scheduling algorithm called Heterogeneous Earliest Finish Time (HEFT), suitably enhanced for the Jupiter system"
featured: false
publication: "*arXiv preprint arXiv:1912.10643*"# Summary. An optional shortened abstract.
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

url_pdf: https://arxiv.org/abs/1912.10643
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


