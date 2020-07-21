---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Infrastructure LiDAR Sensing"
summary: "Working on novel point cloud registration algorithms for infrastructure LiDARs (with different locations and orientations). Also working on algorithms for fine-grain vehicle tracking using a stitched point cloud to augment autonomous driving."
authors: []
tags: []
categories: []
date: 2020-07-21T10:29:33-07:00

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


## **Why Infrastructure LiDAR?**
Future Cities will have LiDAR in the road intersections or on the side of a road.
Infrastructure LiDAR can augment autonomous driving and can provide lot more fine grain surveillance.

![infra](/img/whyinfra.png)


## **Our Objectives**
We are working on deveoping novel point cloud registration algorithms for infrastructure LiDARs (with different locations and orientations) as well as algorithms for fine-grain vehicle tracking using a stitched point cloud to augment autonomous driving.

### Point Cloud Registration (Combining multiple LiDAR data):
1. A single LiDAR can not provide complete information due to line-of-sight blocking, range, and FoV
2. A single LIDAR data can be very sparse and can miss objects.
3. Multiple spatially distributed LiDAR data, once combined, will have more complete information.
![infra](/img/infra1.png)

We are working on deveoping novel point cloud registration algorithms for infrastructure LiDARs (with different locations and orientations).
![infra](/img/infra2.png)


### Detecting and Tracking Object
LiDAR only generate a point cloud for objects without any info on 
1. Whether the two points belong to the same objects?
2. What type of object is it?
3. What are some unique identifiers?

We are working on fine-grain localization and tracking of vehicles using a stitched point cloud to augment autonomous driving; we leverage couple of common facts:
1. LiDAR can distinguish between static and dynamic objects. 
2. For two consecutive frames: 
	* Points related to static objects will remain mostly unchanged
	* Points related to dynamic objects will move.

<iframe src="https://drive.google.com/file/d/1ByhasrYdx8P3X17XoZPJIbxrAcdbYyxd/preview" width="640" height="480"></iframe>


