---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "[ECCV`18] Task-Aware Image Downscaling"
authors: [Myungsub Choi, Heewon Kim, Kyoung Mu Lee]
date: 2018-10-06T17:38:28+09:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-17T17:38:28+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Task-Aware Image Downscaling"
publication_short: "TAID"

abstract: "Image downscaling is one of the most classical problems in computer vision that aims to preserve the visual appearance of the original image when it is resized to a smaller scale. Upscaling a small image back to its original size is a difficult and ill-posed problem due to information loss that arises in the downscaling process. In this paper, we present a novel technique called task-aware image downscaling to support an upscaling task. We propose an auto-encoder-based framework that enables joint learning of the downscaling network and the upscaling network to maximize the restoration performance. Our framework is efficient, and it can be generalized to handle an arbitrary image resizing operation. Experimental results show that our task-aware downscaled images greatly improve the performance of the existing state-of-the-art super-resolution methods. In addition, realistic images can be recovered by recursively applying our scaling model up to an extreme scaling factor of x128. We also validate our model’s generalization capability by applying it to the task of image colorization."

# Summary. An optional shortened abstract.
summary: ""

tags: [image downscaling, super-resolution, deep learning]
categories: [SR]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://openaccess.thecvf.com/content_ECCV_2018/papers/Heewon_Kim_Task-Aware_Image_Downscaling_ECCV_2018_paper.pdf
url_code:
url_dataset:
url_poster:
url_project:
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
