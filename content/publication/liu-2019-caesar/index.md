---
title: "Caesar: cross-camera complex activity recognition"
date: 2019-01-01
publishDate: 2020-07-05T17:44:09.687899Z
authors: ["Xiaochen Liu", "Pradipta Ghosh", "Oytun Ulutan", "BS Manjunath", "Kevin Chan", "Ramesh Govindan"]
publication_types: ["1"]
abstract: "Detecting activities from video taken with a single camera is an active research area for ML-based machine vision. In this paper, we examine the next research frontier: near real-time detection of complex activities spanning multiple (possibly wireless) cameras, a capability applicable to surveillance tasks. We argue that a system for such complex activity detection must employ a hybrid design: one in which rule-based activity detection must complement neural network based detection. Moreover, to be practical, such a system must scale well to multiple cameras and have low end-to-end latency. Caesar, our edge computing based system for complex activity detection, provides an extensible vocabulary of activities to allow users to specify complex actions in terms of spatial and temporal relationships between actors, objects, and activities. Caesar converts these specifications to graphs, efficiently monitors camera feeds, partitions processing between cameras and the edge cluster, retrieves minimal information from cameras, carefully schedules neural network invocation, and efficiently matches specification graphs to the underlying data in order to detect complex activities. Our evaluations show that Caesar can reduce wireless bandwidth, on-board camera memory, and detection latency by an order of magnitude while achieving good precision and recall for all complex activities on a public multi-camera dataset"
featured: false
publication: "*Proceedings of the 17th Conference on Embedded Networked Sensor Systems (Sensys)*"
# Summary. An optional shortened abstract.
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

url_pdf: https://dl.acm.org/citation.cfm?id=3360041
url_code: https://github.com/USC-NSL/Caesar/
url_dataset:
url_poster:
url_project: project/smartcity/
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=HpYSUHRWwRI&feature=youtu.be

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
projects: ["smartcity"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


