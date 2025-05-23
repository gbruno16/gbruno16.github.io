---
title: "The Challenges of the Nonlinear Regime for Physics-Informed Neural Networks" 
date: 2024-09-28
tags: ["Physics-Informed Neural Networks", "Neural Tangent Kernel", "Nonlinear PDEs", "Second-order optimization"]
author: ["Andrea Bonfanti", "Giuseppe Bruno", "Cristina Cipriani"]
description: "" 
summary: "The Neural Tangent Kernel (NTK) viewpoint is widely employed to analyze the training dynamics of overparameterized Physics-Informed Neural Networks (PINNs). However, unlike the case of linear Partial Differential Equations (PDEs), we show how the NTK perspective falls short in the nonlinear scenario. Specifically, we establish that the NTK yields a random matrix at initialization that is not constant during training, contrary to conventional belief. Another significant difference from the linear regime is that, even in the idealistic infinite-width limit, the Hessian does not vanish and hence it cannot be disregarded during training. This motivates the adoption of second-order optimization methods. We explore the convergence guarantees of such methods in both linear and nonlinear cases, addressing challenges such as spectral bias and slow convergence. Every theoretical result is supported by numerical examples with both linear and nonlinear PDEs, and we highlight the benefits of second-order methods in benchmark test cases." 
publisher: "NeurIPS 2024 [Poster]"
link: "https://arxiv.org/abs/2402.03864"
cover:
    image: "paper2_ns.png"
    alt: "Navier Stokes equations"
    relative: true
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "Journal of Canine Science"

---

---

##### Download

+ [Paper](paper2.pdf)
+ [Online appendix](appendix2.pdf)
+ [Code and data](https://github.com/pmichaillat/wunk-model)

---

##### Abstract

This paper studies the pulmonary efficiency of sausage dogs. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur: $\sin(\theta) = x^2 - \exp(1+\chi)$. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor $\zeta$ incididunt ut labore et dolore magna aliqua: $p(x) = \int \cos(\zeta) d\zeta - \theta$. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

---

##### Figure 2: Dimensions of a sausage dog

![](paper2.png)

---

##### Citation

Prinzel, Florianus, and Moritz-Maria von Igelfeld. 2004. "The Finer Points of Sausage Dogs." *Journal of Canine Science* 43 (2): 89–109. http://www.alexandermccallsmith.com/book/the-finer-points-of-sausage-dogs.

```BibTeX
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
+ [Wikipedia entry](https://en.wikipedia.org/wiki/The_Finer_Points_of_Sausage_Dogs)
