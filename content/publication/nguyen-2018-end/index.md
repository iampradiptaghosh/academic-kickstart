---
title: "End-to-End Network Performance Monitoring for Dispersed Computing"
date: 2018-01-01
publishDate: 2020-07-05T17:44:09.681009Z
authors: ["Quynh Nguyen", "Pradipta Ghosh", "Bhaskar Krishnamachari"]
publication_types: ["1"]
abstract: "With a growing demand for computationally intensive applications with widely distributed data sources, there is an increased need for dispersed computing systems that can schedule computation on cloud nodes across a network. A key challenge in dispersed computing is the need to characterize the end to end network performance for data transfer between compute points and measure it at run-time so that  optimized computation scheduling decisions can be made. To address this challenge, we empirically study file transfer times between geographically dispersed cloud computing points using SCP (secure copy). We show, to our knowledge for the first time, that the end to end file transfer latency experienced by this widely-used protocol is better modelled to have a quadratic dependency on the file size (instead of a simple linear dependency that would be expected if the network were treated as an bit-pipe with a deterministic average bandwidth). We incorporate this observation into the design of a real-time network profiler for dispersed computing that determines best fit quadratic regression parameters between each pair of nodes and reports them to the scheduler node. Our end to end network quadratic latency profiler has been released as a key part of an open source tool dispersed computing profiler called DRUPE, and also as part of a DAG-based dispersed computing scheduling tool called CIRCE."
featured: false
publication: "*2018 International Conference on Computing, Networking and Communications (ICNC)*"
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

url_pdf: http://anrg.usc.edu/www/papers/DispersedNetworkProfiler_ICNC2018.pdf
url_code: https://github.com/ANRGUSC/DRUPE
url_dataset:
url_poster:
url_project: project/dcp/
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


