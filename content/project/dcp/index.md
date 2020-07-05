---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dispersed Mobile Computing for Edge Devices"
summary: "This project is on the cutting edge field of *Dispersed Computing* and focused on leveraging all the available computation resources in the communication path from an end device to a cloud."
authors: []
tags: ["rpi", "cloud-computing"]
categories: []
date: 2019-07-05T10:51:31-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This project is on the cutting edge field of *Dispersed Computing* and focused on leveraging all the available computation resources in the communication path from an end device to a cloud (including processing capable routers) for timely and optimized processing of the data by jointly optimizing the computation costs and the communication overhead costs.  A key challenge of this project is the implementation of a Python-based dispersed computing system that would real-time monitor the network traffic and available computation capable node resources to optimally distribute the execution of a networked set of tasks which can be represented as a Directed Acyclic Graph (DAG) task graph. My main contributions to this project involve but not limited to:

* Design and development of a 50 node Raspberry PI 3 cluster with Kubernetes (a docker orchestration tool) support. 
* Implementation of a Kubernetes cluster of 100 carefully chosen geographically distributed cloud Virtual Machines from Digital Ocean.
* Development of the Jupiter Orchestrator which is a Kubernetes based open-source customized docker orchestration tool for Dispersed Computing. The Jupiter tool consists of three main components of Dispersed Computing i.e, Profilers (Network and Resource), Scheduler of DAG-based tasks, and CIRCE -- dispatcher of the tasks according to the scheduler outputs and handler of the inter-task communication. 
