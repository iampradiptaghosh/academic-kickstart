---
title: "ARREST: A RSSI Based Approach for Mobile Sensing and Tracking of a Moving Object"
date: 2019-01-01
publishDate: 2020-07-05T17:44:09.679248Z
authors: ["Pradipta Ghosh", "Jason A Tran", "Bhaskar Krishnamachari"]
publication_types: ["2"]
abstract: "We present Autonomous Rssi based RElative poSitioning and Tracking (ARREST), a new robotic sensing system for tracking and following a moving, RF-emitting object, which we refer to as the Leader, solely based on signal strength information. Our proposed tracking agent, which we refer to as the TrackBot, uses a single rotating, off-the-shelf, directional antenna, novel angle and relative speed estimation algorithms, and Kalman filtering to continually estimate the relative position of the Leader with decimeter level accuracy (which is comparable to a state-of-the-art multiple access point based RF-localization system) and the relative speed of the Leader with accuracy on the order of 1 m/s. The TrackBot feeds the relative position and speed estimates into a Linear Quadratic Gaussian (LQG) controller to generate a set of control outputs to control the orientation and the movement of the TrackBot. We perform an extensive set of real world experiments with a full-fledged prototype to demonstrate that the TrackBot is able to stay within 5m of the Leader with: (1) more than 99% probability in line of sight scenarios, and (2) more than 75% probability in no line of sight scenarios, when it moves 1.8X faster than the Leader"
featured: true
math: true
publication: "In *IEEE Transactions on Mobile Computing* 19.6 (2019),pp. 1260–1273"
project: [rwsn]
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

url_pdf: https://ieeexplore.ieee.org/abstract/document/8680705
url_code:
url_dataset:
url_poster:
url_project: project/rwsn/
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=kbfsYWE_L0o&t=41s

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
