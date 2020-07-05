---
title: "Romano: A novel overlay lightweight communication protocol for unified control and sensing of a network of robots"
date: 2017-01-01
publishDate: 2020-07-05T17:44:09.693629Z
authors: ["Pradipta Ghosh", "Jason A Tran", "Daniel Dsouza", "Nora Ayanian", "Bhaskar Krishnamachari"]
publication_types: ["3"]
abstract: "We present the Robotic Overlay coMmunicAtioN prOtocol (ROMANO), a lightweight, application layer overlay communication protocol for a unified sensing and control abstraction of a network of heterogeneous robots mainly consisting of low power, low-compute-capable robots. ROMANO is built to work in conjunction with the well-known MQ Telemetry Transport for Sensor Nodes (MQTT-SN) protocol, a lightweight publish-subscribe communication protocol for the Internet of Things and makes use its concept of topics to designate the addition and deletion of communication endpoints by changing the subscriptions of topics at each device. We also develop a portable implementation of ROMANO for low power IEEE 802.15.4 (Zigbee) radios and deployed it on a small testbed of commercially available, low-power, and low-compute-capable robots called Pololu 3pi robots. Based on a thorough analysis of the protocol on the real testbed, as a measure of throughput, we demonstrate that ROMANO can guarantee more than a 99.5% message delivery ratio for a message generation rate up to 200 messages per second. The single hop delays in ROMANO are as low as 20ms with linear dependency on the number of robots connected. These delay numbers concur with typical delays in 802.15.4 networks and suggest that ROMANO does not introduce additional delays. Lastly, we implement four different multi-robot applications to demonstrate the scalability, adaptability, ease of integration, and reliability of ROMANO"
featured: false
publication: "*arXiv preprint arXiv:1709.07555*"
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

url_pdf: https://arxiv.org/abs/1709.07555
url_code: https://github.com/ANRGUSC/ROMANO
url_dataset:
url_poster:
url_project: project/rwsn/
url_slides:
url_source:
url_video: http://tiny.cc/anrg-romano

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
projects: ["rwsn"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
