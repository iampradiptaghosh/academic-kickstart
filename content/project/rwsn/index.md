---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Wireless Robotic IoT Systems"
summary: "Integration of Robots in IoT system for providing temporary communication platfrom and sensing"
authors: []
tags: ["rwsn", "iot"]
categories: []
date: 2018-07-05T10:51:51-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

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
This umbrella projects includes many sub-projects as follows. 

* **Survey of Networking Issues and Potential areas of Research in a Wireless Network of Mobile Robots**
![robot](/img/robo_sensor_illustration_new.png)
* **ARREST--A RSSI Based Approach for Relative Positioning and  Tracking of a Moving Object:**
Developed a new robotic sensing system for tracking/following a moving, RF-emitting object (Leader) solely based on signal strength information. The tracking robot (TrackBot) uses a single rotating, off-the-shelf, directional antenna, novel angle and relative speed estimation algorithms, and Kalman filtering.  A full-fledged prototype system is built for extensive real-world evaluation and to demonstrate the performance.
![robot](/img/robot_sch.jpg)

* **IRIS--A Robotic Wireless Networking Testbed:**
Designed the architecture of the Intelligent Robotic IoT System (IRIS) testbed which is envisioned as an in-house, cutting-edge, open source testbed for robotic network related experimentation.
Co-lead a team of six researchers to build the current version of the testbed that consists of 7 mobile easily configurable Pololu 3pi robotic nodes with IEEE 802.15.4 connectivity via an onboard OpenMote and Mbed LPC1768 devices.
![robot](/img/iris.jpg)

* **ROMANO--Overlay Lightweight Communication Protocol for Unified Control and Sensing of a Network of Robots:**
Developed and implemented (on the IRIS testbed) the ROMANO protocol, an end-to-end overlay communication protocol for a simple unified abstraction of real-time data sharing and robotic control in a network of robots. This is a lightweight, application layer publish-subscribe protocol that is an alternative to the XML-RPC  based bandwidth-heavy communication in Robot Operating System (ROS). 
![router](/img/romano_archi.jpg)

* **Robotic Router Placement Optimization Based on Practical Communication Model Including Interference:**
Theoretically modeled and simulated an optimized robotic router placement algorithm that incorporates the effect of RF interference.                         
Moreover, modeled certain theoretical performance bounds of such systems such as interference power bound.

![router](/img/robo_router_illustration_new.jpg)
                      

