---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Low Power Routing for Internet of Things"
summary: "Optimized routing algorithms for Internet of Things"
authors: []
tags: ["wsn", "iot"]
categories: []
date: 2017-07-05T10:52:22-07:00

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
This project includes three sub-projects.

* **Heat Diffusion Collection Protocol Implementation for Energy Efficient Data Collection in any IoT Network:** 
Developed and implemented a practical version of a theoretical Back-pressure routing algorithm called the Heat Diffusion (HD) algorithm in the Contiki OS. We refer to this algorithm as the Heat Diffusion Collection Protocol (HDCP). I analyzed its performance for a varying set of network conditions in static settings in a 100 node testbed called the Tutornet.

* **Distributed Hole Detection Methods in IoT and WSN:** 
Developed distributed techniques for hole detection in a WSN that are based on popular computation geometry tools such as Delaunay triangulation of the underlying communication graph and a graph's Gaussian curvature. 

* **IoTSC Testbed:**  I am also a key member of a campus-wide IoT testbed deployment initiative by the USC Autonomous Networks Research Group (ANRG) and the USC Viterbi Center for CPS and IoT (CCI). The testbed, currently referred to as IoTSC, aims to deploy 50 Raspberry Pi-based IoT boxes across the USC Park Campus for IoT related experimentation purposes. Each box is equipped with a range of sensors, such as temperature, gas, and humidity sensors, and at least three different communication stacks (Bluetooth, WiFi, and 802.15.4). Many of the nodes are also equipped with SDRs (USRP b200 mini and HackRF) and LoRa radios.
