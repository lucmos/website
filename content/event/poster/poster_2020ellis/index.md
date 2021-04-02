---
title: Learning Set Operations for Deformable Shapes

event: ELLIS Workshop on Geometric and Relational Deep Learning
event_url: https://geometric-relational-dl.github.io/

location: Amsterdam (virtual)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: |2-
  *ELLIS Workshop on Geometric and Relational Deep Learning*

abstract: |2-
  Given several parts of a single shape, how can we “stitch” them together so as to reconstruct the shape? Alternatively, how can we remove a fixed part from a given shape? What if each part deforms independently? Crucially, *how can we solve these tasks without requiring a correspondence*?

  The problem of solving rigid or non-rigid shape puzzles is extremely hard (see Litany et al. [2016]). It involves several sub-problems, including shape discretization, matching, and generation, and has been at the heart of applied data sciences for decades. We propose to address this task by side-stepping the need to solve many of these sub-problems. To do so, we resort to a recent family of computational techniques revolving around the computation of the Laplacian eigenvalues of the given shapes.

  It has long been known that the shape of an object determines the spectrum of the Laplacian, where geometric information of the shape itself is encoded. Recent works (see Cosmo et al. [2019], Rampini et al. [2019]) have shown that the inverse problem to recover the shape from its Laplacian spectrum is approachable in practice. We claim that solving a non-rigid shape puzzle can be fully phrased in terms of the shape spectra, where we devise a learning scheme to perform set operations directly on these spectra and then, at a second stage, reconstruct the desired shape from the estimated spectrum.

  Learning to perform set operations in the space of eigenvalues enables an isometry invariant, correspondence-free formulation of the problem. The lack of a require ment for an explicit correspondence between the different parts allows us to operate with heterogeneous datasets (e.g. point clouds together with meshes) at varying discretization quality, resulting in an especially robust pipeline that can be adopted in several practical settings.

  ## References

  - Luca Cosmo, Mikhail Panine, Arianna Rampini, Maks Ovsjanikov, Michael M Bronstein, and Emanuele Rodolà. Isospectralization, or how to hear shape, style, and correspondence. In *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, pages 7529–7538, 2019.
  - O. Litany, E. Rodolà, A. M. Bronstein, M. M. Bronstein, and D. Cremers. Non-rigid puzzles. *Computer Graphics Forum*, 35(5):135–143, 2016.
  - Arianna Rampini, Irene Tallini, Maks Ovsjanikov, Alex M Bronstein, and Emanuele Rodolà. Correspondence-free region localization for partial shape similarity via hamiltonian spectrum alignment. In *International Conference on 3D Vision (3DV)*, 2019.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-04-24"
# date_end: "2020-04-25"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2020-01-01T00:00:00Z"

authors:
  - admin
  - Filippo Maggioli
  - Or Litany
  - Simone Melzi
  - Maks Ovsjanikov
  - Leonidas Guibas
  - Emanuele Rodolà
tags: [poster]


# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Smart

links:
- icon: youtube
  icon_pack: fab
  name: Video
  url: https://www.youtube.com/watch?v=wdjX4TlmzHA

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example

---
