---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Synthesis of Large-Scale Instant IoT Networks"
authors: ["Pradipta Ghosh", "Jonathan Bunton", "Dimitrios Pylorof", "Marcos Vieira", "Kevin Chan", "Ramesh Govindan", "Gaurav Sukhatme", "Paulo Tabuada", "Gunjan Verma"]
date: 2021-07-26T10:49:26-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-26T10:49:26-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Mobile Computing* "
publication_short: ""

abstract: "While most networks have long lifetimes, temporary network infrastructure is often useful for special events, pop-up retail, or disaster response. An instant IoT network is one that is rapidly constructed, used for a few days, then dismantled. We consider the synthesis of instant IoT networks in urban settings. This synthesis problem must satisfy complex and competing constraints: sensor coverage, line-of-sight visibility, and network connectivity. The central challenge in our synthesis problem is quickly scaling to large regions while producing cost-effective solutions. We explore two qualitatively different representations of the synthesis problems using satisfiability modulo convex optimization (SMC), and mixed-integer linear programming (MILP). The former is more expressive, for our problem, than the latter, but is less well-suited for solving optimization problems like ours. We show how to express our network synthesis in these frameworks. To scale to problem sizes beyond what these frameworks are capable of, we develop a hierarchical synthesis technique that independently synthesizes networks in sub-regions of the deployment area, then combines these. We find that, while MILP outperforms SMC in some settings for smaller problem sizes, the fact that SMC's expressivity matches our problem ensures that it uniformly generates better quality solutions at larger problem sizes."

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

url_pdf: https://ieeexplore.ieee.org/abstract/document/9495234
url_code:
url_dataset:
url_poster: 
url_project: project/smartcity
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
