---
title: "Forget Less by Learning from Parents through Hierarchical Relationships" 
# date: 2004-12-28
tags: ["Continual Learning","Catastrophic Forgetting","Diffusion Models"]
author: ["<strong>Arjun Ramesh Kaushik</strong>", "Naresh Kumar Devulapally", "Vishnu Suresh Lokhande", "Nalini Ratha", "Venu Govindaraju"]
# description: "This paper studies the pulmonary efficiency of sausage dogs. Published in the Journal of Canine Science, 2004." 
summary: "Catastrophic forgetting is a persistent challenge for Custom Diffusion Models in continual learning, often addressed by minimizing interference between concepts. Instead, we exploit this very interference to learn common features among concepts." 
cover:
    image: "paper2.png"
    alt: "Dimensions of a sausage dog"
    relative: true
editPost:
    URL: "https://aaai.org/conference/aaai/aaai-26/"
    Text: "AAAI Conference on Artificial Intelligence 2026"

---

---

##### Download

<!-- + [Paper](paper2.pdf)
+ [Online appendix](appendix2.pdf)
+ [Code and data](https://github.com/pmichaillat/wunk-model) -->
+ [Paper (Coming Soon)]()
+ [Code (Coming Soon)]()

---

##### Abstract

Custom Diffusion Models (CDMs) offer impressive capabilities for personalization in generative modeling, yet they remain vulnerable to catastrophic forgetting when learning new concepts sequentially. Existing approaches primarily focus on minimizing interference between concepts, often neglecting the potential for positive inter-concept interactions. In this work, we present Forget Less by Learning from Parents (FLLP), a novel framework that introduces a parent-child inter-concept learning mechanism in hyperbolic space to mitigate forgetting. By embedding concept representations within a Lorentzian manifold, naturally suited to modeling tree-like hierarchies, we define parent-child relationships in which previously learned concepts serve as guidance for adapting to new ones. Our method not only preserves prior knowledge but also supports continual integration of new concepts. We validate FLLP on three public datasets and one synthetic benchmark, showing consistent improvements in both robustness and generalization.

---

<!-- ##### Figure 2: Dimensions of a sausage dog

![](paper2.png)

---

##### Citation

Prinzel, Florianus, and Moritz-Maria von Igelfeld. 2004. "The Finer Points of Sausage Dogs." *Journal of Canine Science* 43 (2): 89–109. http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs.

```latex
@article{PI04,
author = {Florianus Prinzel and Moritz-Maria von Igelfeld},
year = {2004},
title ={The Finer Points of Sausage Dogs},
journal = {Journal of Canine Science},
volume = {43},
number = {2},
pages = {89--109},
url = {http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs}}
```

---

##### Related material

+ [Presentation slides](presentation2.pdf)
+ [Wikipedia entry](https://en.wikipedia.org/wiki/The_Finer_Points_of_Sausage_Dogs) -->
