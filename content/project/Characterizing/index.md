---
title: "Characterizing Topics in Social Media"
summary: "Estimated the genre of social media posts with 90% accuracy"
authors: []
tags: [Network Science, Machine Learning]
categories: []
date: 2022-02-05T11:42:43-05:00

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

- Extracted key response features that depict the dynamics of the conversation under
different subreddits by analyzing a Reddit dataset containing 5K subreddits and 887M
comments
- Utilized machine learning to evaluate the effectiveness of the extracted response
features, which show a 90% accuracy in predicting the genre of Reddit submissions
- Clustered posts within a subreddit with response features, K-means, and PCA to
identify the dominant topics within each subreddit
- Applied the derived response features to accurately detect outlier posts and efficiently predict the viral posts

{{< icon name="download" pack="fas" >}} Download the paper for this project: {{< staticref "uploads/files/Reddit.pdf" "newtab" >}}Reddit{{< /staticref >}}