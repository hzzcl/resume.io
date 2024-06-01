---
title: "Cascaded residual U-net for fully automatic segmentation of 3D carotid artery in high-resolution multi-contrast MR images"
authors:
- admin

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-02-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Physics in Medicine & Biology, 66*(4)"
publication_short: "Phys. Med. Biol."

abstract: Accurate and automatic carotid artery segmentation for magnetic resonance (MR) images is eagerly expected, which can greatly assist a comprehensive study of atherosclerosis and accelerate the translation. Although many efforts have been made, identification of the inner lumen and outer wall in diseased vessels is still a challenging task due to complex vascular deformation, blurred wall boundary, and confusing componential expression. In this paper, we introduce a novel fully automatic 3D framework for simultaneously segmenting the carotid artery from high-resolution multi-contrast MR sequences based on deep learning. First, an optimal channel fitting structure is designed for identity mapping, and a novel 3D residual U-net is used as a basic network. Second, high-resolution MR images are trained using both patch-level and global-level strategies, and the two pre-segmentation results are optimized based on structural characteristics. Third, the optimized pre-segmentation results are cascaded with the patch-cropped MR volume data and trained to segment the carotid lumen and wall. Extensive experiments demonstrate the proposed method outperforms the state-of-the-art 3D Unet-based segmentation models.

# Summary. An optional shortened abstract.
summary: We propose a novel fully automatic 3D framework for simultaneous segmentation of the carotid artery from high-resolution multi-contrast MR sequences based on deep learning, achieving superior performance compared to SOAT 3D Unet-based segmentation models.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://iopscience.iop.org/article/10.1088/1361-6560/abd4bb/meta
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Cascaded_Carotid_Seg**]'
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
