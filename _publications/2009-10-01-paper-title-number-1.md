---
title: "How the Softmax Output is Misleading for Evaluating the Strength of Adversarial Examples"
collection: publications
date: 2018-01-01
permalink: p1
venue: '32nd Conference on Neural Information Processing Systems (NeurIPS), Montréal, Canada <br /> Workshop on Security in Machine Learning (SECML), Poster presentation'
---
**Utku Ozbulak**, Wesley De Neve, Arnout Van Messem  <br /> [Download paper](https://arxiv.org/abs/1811.08577) <br /> [Download poster](http://academicpages.github.io/files/paper2.pdf)

**Abstract**

Even before deep learning architectures became the de facto models for complex computer vision tasks, the softmax function was, given its elegant properties, already used to analyze the predictions of feedforward neural networks. Nowadays, the output of the softmax function is also commonly used to assess the strength of adversarial examples: malicious data points designed to fail machine learning models during the testing phase. However, in this paper, we show that it is possible to generate adversarial examples that take advantage of some properties of the softmax function, leading to undesired outcomes when interpreting the strength of the adversarial examples at hand. Specifically, we argue that the output of the softmax function is a poor indicator when the strength of an adversarial example is analyzed and that this indicator can be easily tricked by already existing methods for adversarial example generation. 
