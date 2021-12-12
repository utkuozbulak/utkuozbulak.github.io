---
title: "Regional Image Perturbation Reduces Lp Norms of Adversarial Examples While Maintaining Model-to-model Transferability"
collection: publications
date: 2020-7-01
permalink: 20-icml
venue: '2020 International Conference on Machine Learning (ICML), Workshop on Uncertainty & Robustness in Deep Learning (UDL) <br />   Poster presentation'
---
**Utku Ozbulak**, Jonathan Peck, Wesley De Neve, Bart Goossens, Yvan Saeys, Arnout Van Messem <br /> [Download paper](https://arxiv.org/abs/2007.03198) <br /> [Download code](https://github.com/utkuozbulak/regional-adversarial-perturbation)

**Abstract**
Regional adversarial attacks often rely on complicated methods for generating adversarial perturbations, making it hard to compare their efficacy against well-known attacks. In this study, we show that effective regional perturbations can be generated without resorting to complex methods. We develop a very simple regional adversarial perturbation attack method using cross-entropy sign, one of the most commonly used losses in adversarial machine learning. Our experiments on ImageNet with multiple models reveal that, on average, 76% of the generated adversarial examples maintain model-to-model transferability when the perturbation is applied to local image regions. Depending on the selected region, these localized adversarial examples require significantly less Lp norm distortion (for p∈{0,2,∞}) compared to their non-local counterparts. These localized attacks therefore have the potential to undermine defenses that claim robustness under the aforementioned norms. 
