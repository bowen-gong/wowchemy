---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "High Performance Parallel Computing for PDE Solver"
summary: "Designed and implementd a parallel solver for PDEs"
authors: []
tags: [Parallel Computing]
categories: []
date: 2022-02-05T11:58:01-05:00

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

- Designed and developed a parallel algorithm with CUDA and MPI to solve PDE equations to computation cost
- Evaluated the performance of the implemented algorithms based on the weak scaling and strong scaling study
- Implemented the parallel I/O to allow massive concurrent read/write operations to a common file

{{< icon name="download" pack="fas" >}} Download the report for this project: {{< staticref "uploads/parallel.pdf" "newtab" >}}Parallel PDE solver{{< /staticref >}}