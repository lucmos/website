---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Spectral Unions of Partial Deformable 3D Shapes
subtitle: ''
summary: ''
authors:
- Luca Moschella
- Simone Melzi
- Luca Cosmo
- Filippo Maggioli
- Or Litany
- Maks Ovsjanikov
- Leonidas Guibas
- Emanuele Rodolà
tags:
- '"Computer Science - Computational Geometry"'
- '"Computer Science - Graphics"'
- '"Computer Science - Machine Learning"'
categories: []
date: '2021-03-31'
lastmod: 2021-04-02T11:32:00+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# links:
# - icon: youtube
#   icon_pack: fab
#   name: Video
#   url: https://www.youtube.com/watch?v=SeZWxF15bbs

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-04-02T09:31:59.888843Z'
publication_types:
- '3'
abstract: Spectral geometric methods have brought revolutionary changes to the field
  of geometry processing -- however, when the data to be processed exhibits severe
  partiality, such methods fail to generalize. As a result, there exists a big performance
  gap between methods dealing with complete shapes, and methods that address missing
  geometry. In this paper, we propose a possible way to fill this gap. We introduce
  the first method to compute compositions of non-rigidly deforming shapes, without
  requiring to solve first for a dense correspondence between the given partial shapes.
  We do so by operating in a purely spectral domain, where we define a union operation
  between short sequences of eigenvalues. Working with eigenvalues allows to deal
  with unknown correspondence, different sampling, and different discretization (point
  clouds and meshes alike), making this operation especially robust and general. Our
  approach is data-driven, and can generalize to isometric and non-isometric deformations
  of the surface, as long as these stay within the same semantic class (e.g., human
  bodies), as well as to partiality artifacts not seen at training time.
publication: '*arXiv*'
url_pdf: http://arxiv.org/abs/2104.00514
---
