---
title: "Sensing the Sensor: Estimating Camera Properties with Minimal Information"
date: 2022-02-01
publishDate: 2022-02-01T17:44:09.690475Z
authors: ["Pradipta Ghosh", "Xiaochen Liu", "Hang Qiu", "Marcos A. M. Vieira", "Gaurav S. Sukhatme", "Ramesh Govindan"]
publication_types: ["3"]
abstract: "Public outdoor surveillance cameras often have limited metadata describing their properties. Frequently, a public camera’s precise position, orientation, focal length, and image center are unknown; these attributes are necessary to precisely pinpoint the location of events seen in the camera. In this article, we ask: what is the minimal information needed to accurately estimate these properties for public cameras? We show, using a judicious combination of projective geometry, neural networks, and crowd-sourced annotations from human workers, that it is possible to, for example, localize 95% of the cameras in our test data set to within 12 m using a single image taken from the camera. This performance is an order of magnitude better than PoseNet, a state-of-the-art neural network that needs significantly more information than our approach, and can only estimate position and orientation (and not other properties). Finally, we show that the camera’s inferred pose and properties can help design a number of virtual sensors, all of which have good accuracy."
featured: true
publication: "*ACM Transactions on Sensor Networks*, Volume 18, Issue 2, May 2022, Article No.: 28, pp 1–26"
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

url_pdf: https://dl.acm.org/doi/10.1145/3508393
url_code:
url_dataset:
url_poster:
url_project: project/smartcity/
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
projects: ["smartcity"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

