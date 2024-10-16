---
title: "Adaptive Functional Principal Components Analysis"
authors:
- admin
- Valentin Patilea
- Nicolas Klutchnikoff
date: "2023-07-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Accepted, Journal of the Royal Statistical Society, Series B (Statistical Methodology)"
publication_short: ""

abstract: "Functional data analysis (FDA) almost always involves smoothing discrete observations into curves, because they are never observed in continuous time and rarely without error. Although smoothing parameters affect the subsequent inference, data-driven methods for selecting these parameters are not well-developed, frustrated by the difficulty of using all the information shared by curves while being computationally efficient. 
On the one hand, smoothing individual curves in an isolated, albeit sophisticated way, ignores useful signals present in other curves. On the other hand, bandwidth selection by automatic procedures such as cross-validation after pooling all the curves together quickly become computationally unfeasible due to the large number of data points. 
In this paper we propose a new data-driven, adaptive kernel smoothing method, specifically tailored for functional principal components analysis (FPCA) through the derivation of sharp, explicit risk bounds for the eigen-elements. The minimization of these quadratic risk bounds provide refined, yet computationally efficient bandwidth rules for each eigen-element separately. Both common and independent design cases are allowed.  
Rates of convergence for the adaptive eigen-elements estimators are derived. 
An extensive simulation study, designed in a versatile manner to closely mimic characteristics of real data sets, support our methodological contribution, which is available for use in the R package FDAdapt."

tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/abs/2306.16091
url_code: 'https://github.com/sunnywang93/FDAdapt'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---


