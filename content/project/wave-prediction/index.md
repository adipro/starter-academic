---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fast deterministic wave-by-wave prediction of real ocean waves"
summary: "It is well-known that the power production of a wave energy converter can be significantly increased if we can tune it to respond optimally to each incoming wave. This project aims to develop fast wave-by-wave prediction tools to accurately predict weakly nonlinear waves in unidirectional and multidirectional seas. Applications range from wave energy control to offshore operations and recreational activities."
authors: []
tags: [wave prediction, wave energy]
categories: []
# date: 2021-05-31T14:36:29+08:00

editable: true

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
url_video: "https://youtu.be/LDRjLnrcUc0"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

It is well-known that the power production of a wave energy converter can be significantly increased if we can tune it to respond optimally to each incoming wave.
<!-- This is possible if we know in advance what the incoming waves will look like some wave periods into the future.  -->
In this project, our PhD student Thobani Hlophe is developing fast prediction tools to accurately predict weakly nonlinear waves in unidirectional and multidirectional seas. The method involves simple extension of the wave record using the properties of the latest values in the record and the statistics of the sea state, combining this with approximate second-order corrections to the surface elevation. Propagation in space and time is then possible using Fast Fourier Transform, ensuring its computational efficiency.
This project is co-supervised by [Dr. Hugh Wolgamot](https://research-repository.uwa.edu.au/en/persons/hugh-wolgamot), [Prof. Paul H. Taylor](https://research-repository.uwa.edu.au/en/persons/paul-taylor), [Dr. Jana Orszaghova](https://research-repository.uwa.edu.au/en/persons/jana-orszaghova), and [A/Prof. Scott Draper](https://research-repository.uwa.edu.au/en/persons/scott-draper).
