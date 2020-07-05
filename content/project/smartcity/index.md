---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sensing in Smart Cities"
summary: "This research can be categorized into three categories: Sensing Smart City Resources (e.g., public cameras), Network Synthesis, and  Cross Camera Activity Detection."
authors: []
tags: ["iot", "vision"]
categories: []
date: 2020-07-05T10:51:59-07:00

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
This ongoing research can be categorized into three categories: Sensing Smart City Resources (e.g., public cameras), Network Synthesis, and Cross Camera Activity Detection. 

1. **Sensing Smart City Resources:** This  category of the research focuses on automatically identifying and characterizing a wide range of sensors (cameras, microphones) in a Large City that we can leverage for many applications such as search and rescue missions, personalized fine-grain navigation, and autonomous driving assistance. 
![smartcity](/img/sensecam.png)

2. **Network Synthesis:** The second part of the research focus on optimal usage of these public resources in smart city applications by forming an optimized network with them. For example, assume that we need an area to be monitored constantly during a search and rescue mission. In that case, we might have either a lot of unnecessary cameras or might have less than the required number of cameras already present. Building upon modern constrained optimization techniques, we are working on developing techniques that can subselect the optimal set of sensors as well as inform us if more sensors need to be deployed. If more sensors are required to be deployed, the method also outputs what are the best locations to place them. 
![synthesis](/img/synthesis.png)

3. **Cross Camera Activity Detection:** The third part of research focus on detecting complex activities in smart cities. A complex activity can be “a person getting off an car then smoking then talking to another person and walking together”. While a human can easily interpret these actions, for a machine it is very hard to automatically detect such activity. In addition, if these actions occur across multiple cameras i.e., some part of the activity in one camera and the other in a different camera, then it is even a tougher problem. We have developed a system that can perform cross camera activity detection. 
![caeser](/img/caeser.gif)
