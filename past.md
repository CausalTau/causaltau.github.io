---
layout: page
title: Past Talks
order: 4
---

<!-- ## Past Talks and Recordings -->

* Thursday, February 3rd, 2022 - **Domain Generalization in a Causal Perspective: Deconfounding the Domain Biases** by Shiyang Yan (INRIA, TAU Team) [[Video]()] [[Slides]()]
  - **Abstract**: Domain Generalization (DG), focusing on out-of-distribution generalization (Wang et al., 2021), aims to train a model on several source domains, and apply it on an unknown target domain. DG faces a key difficulty, the fact that each source domain suffers from a dataset bias. The contribution of the paper is to tackle DG in a causal perspective, where the source biases are viewed as confounders. Taking inspiration from the Deconfounder approach (Wang and Blei 2019, 2021), a non-linear independent component analysis (ICA) is used to learn substitute hidden confounders (SHCs). To mitigate the non-identifiability of the SHCs,  a novel adversarial contrastive learning scheme is used to learn domain invariant and mutually independent SHCs. The merits of the approach are comparatively demonstrated on several challenging DG benchmarks, yielding state-of-art performances. Ablation studies are conducted to determine the respective impact of the ICA model and of the contrastive learning scheme.
  - **References**
    - Wang, Y. and Blei, D. M. [The blessings of multiple causes](https://www.tandfonline.com/doi/full/10.1080/01621459.2019.1686987). Journal of the American Statistical Association, 114(528): 1574–1596, 2019.
    - Wang, Z., Loog, M., and van Gemert, J. [Respecting domain relations: Hypothesis invariance for domain generalization](https://arxiv.org/abs/2010.07591). In The International Conference on Pattern Recognition (ICPR), 2021.
  - **Bio**: Shiyang Yan is presently a postdoc researcher in the TAU research team of the National Institute for Research in Digital Science and Technology (INRIA), Paris, France. Prior to that, he worked as a university lecturer at NUIST, China from 2020 to 2021. Previously, he has worked as a postdoc researcher at Queen’s University Belfast, UK from 2019-2020. He received a Ph.D. degree from the University of Liverpool, UK, in 2018. He received his Master's degree from Hohai University in 2015. His research interests include causal inference, reinforcement learning, and attention mechanism.  