---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Metric Based Few-Shot Graph Classification'
subtitle: ''
summary: ''
authors:
- Donato Crisostomi
- Simone Antonelli
- Valentino Maiorca
- admin
- Riccardo Marin
- Emanuele Rodolà
tags:
- Machine Learning (cs.LG)
- Artificial Intelligence (cs.AI)

categories: []
date: '2022-06-08'
lastmod: 2022-03-31T14:18:10+02:00
featured: false
draft: false

links:
- icon:  chalkboard-user
  icon_pack: fas
  name: 'arXiv'
  url: https://arxiv.org/abs/2206.03695


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-03-31T12:18:10.158476Z'
publication_types:
- '3'
abstract: 'Many modern deep-learning techniques do not work without enormous datasets. At the same time, several fields demand methods working in scarcity of data. This problem is even more complex when the samples have varying structures, as in the case of graphs. Graph representation learning techniques have recently proven successful in a variety of domains. Nevertheless, the employed architectures perform miserably when faced with data scarcity. On the other hand, few-shot learning allows employing modern deep learning models in scarce data regimes without waiving their effectiveness. In this work, we tackle the problem of few-shot graph classification, showing that equipping a simple distance metric learning baseline with a state-of-the-art graph embedder allows to obtain competitive results on the task.While the simplicity of the architecture is enough to outperform more complex ones, it also allows straightforward additions. To this end, we show that additional improvements may be obtained by encouraging a task-conditioned embedding space. Finally, we propose a MixUp-based online data augmentation technique acting in the latent space and show its effectiveness on the task.'
publication: '*arXiv*'

---
