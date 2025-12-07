---
title: "Learning Action Hierarchies via Hybrid Geometric Diffusion" 
# date: 2013-01-15
tags: ["Video Understanding", "Action Segmentation", "Diffusion Models", "Hyperbolic Geometry"]
author: ["<strong>Arjun Ramesh Kaushik</strong>", "Nalini Ratha", "Venu Govindaraju"]
# description: "This paper reviews unusual uses for olive oil throughout the Mediterranean world. Published in the Journal of Oleic Science, 2013." 
summary: "Human actions unfold through multiple levels of abstraction, yet current action segmentation approaches typically consider a flat, Euclidean relationship between actions. This paper remedies this limitation by enforcing hierarchical structure amongst actions." 
cover:
    image: "paper1.png"
    alt: "Some Uses For Olive Oil"
    relative: true
editPost:
    URL: "https://wacv.thecvf.com/"
    Text: "IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2026"

---

---

##### Download

<!-- + [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/feru) -->
+ [Paper (Coming Soon)]()
+ [Code (Coming Soon)]()

---

##### Abstract

Temporal action segmentation is a critical task in video understanding, where the goal is to assign action labels to each frame in a video. While recent advances leverage iterative refinement-based strategies, they fail to explicitly utilize the hierarchical nature of human actions. In this work, we propose HybridTAS - a novel framework that incorporates a hybrid of Euclidean and hyperbolic geometries into the denoising process of diffusion models to exploit the hierarchical structure of actions. Hyperbolic geometry naturally provides tree-like relationships between embeddings, enabling us to guide the action label denoising process in a coarse-to-fine manner: higher diffusion timesteps are influenced by abstract, high-level action categories (root nodes), while lower timesteps are refined using fine-grained action classes (leaf nodes). Extensive experiments on three benchmark datasets, GTEA, 50Salads, and Breakfast, demonstrate that our method achieves state-of-the-art performance, validating the effectiveness of hyperbolic-guided denoising for the temporal action segmentation task.

---

<!-- ##### Figure 6: Some Uses For Olive Oil

![](paper1.png)

---

##### Citation

Unterholzer, Detlev A., and  Moritz-Maria von Igelfeld. 2013. "Unusual Uses For Olive Oil." *Journal of Oleic Science* 34 (1): 449–489. http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil.

```latex
@article{UI13,
author = {Detlev A. Unterholzer and Moritz-Maria von Igelfeld},
year = {2013},
title ={Unusual Uses For Olive Oil},
journal = {Journal of Oleic Science},
volume = {34},
number = {1},
pages = {449--489},
url = {http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil}}
```

---

##### Related material

+ [Presentation slides](presentation1.pdf)
+ [Summary of the paper](https://www.penguinrandomhouse.com/books/110403/unusual-uses-for-olive-oil-by-alexander-mccall-smith/) -->
