---
title: "Forget Less by Learning Together through Concept Consolidation" 
# date: 2025-04-06
tags: ["Continual Learning","Catastrophic Forgetting","Diffusion Models"]
author: ["<strong>Arjun Ramesh Kaushik</strong>", "Naresh Kumar Devulapally", "Vishnu Suresh Lokhande", "Nalini Ratha", "Venu Govindaraju"]
# description: "This paper describes the inner hedgehog, a psychological condition widespread in academia. Published in the Journal of Socio-Experimental Psychology, 2021." 
summary: "Catastrophic forgetting is a persistent challenge for Custom Diffusion Models in continual learning, often addressed by minimizing interference between concepts. Instead, we exploit this very interference to learn common features among concepts." 
cover:
    image: "paper3.png"
    alt: "Vizualisation of an inner hedgehog"
    relative: true
editPost:
    URL: "https://wacv.thecvf.com/"
    Text: "IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2026"

---

---

##### Download

+ [Paper (Coming Soon)]()
+ [Code (Coming Soon)]()

---

##### Abstract
Custom Diffusion Models (CDMs) have gained significant attention due to their remarkable ability to personalize generative processes. However, existing CDMs suffer from catastrophic forgetting when continuously learning new concepts. Most prior works attempt to mitigate this issue under the sequential learning setting with a fixed order of concept inflow and neglect inter-concept interactions. In this work, we propose a novel framework - Forget Less by Learning Together (FL2T) - that enables concurrent and order-agnostic concept learning while addressing catastrophic forgetting. Specifically, we introduce a set-invariant inter-concept learning module where proxies guide feature selection across concepts, facilitating improved knowledge retention and transfer. By leveraging inter-concept guidance, our approach preserves old concepts while efficiently incorporating new ones. Extensive experiments, across three datasets, demonstrates that our method significantly improves concept retention and mitigates catastrophic forgetting, highlighting the effectiveness of inter-concept catalytic behavior in incremental concept learning of ten tasks with at least 2% gain on average Image Alignment scores.

---

<!-- ##### Citation

Schreiber-Ziegler, Hilda, and Moritz-Maria von Igelfeld. 2021. "Your Inner Hedgehog." *Journal of Socio-Experimental Psychology* 131 (2): 1299–1302.

```latex
@article{SZI21,
author = {Hilda Schreiber-Ziegler and Moritz-Maria von Igelfeld},
year = {2021},
title ={Your Inner Hedgehog},
journal = {Journal of Socio-Experimental Psychology},
volume = {131},
number = {2},
pages = {1299--1302}}
```

---

##### Related material

+ [Nontechnical summary](https://www.alexandermccallsmith.com/book/your-inner-hedgehog) -->
