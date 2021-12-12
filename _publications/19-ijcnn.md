---
title: "Not All Adversarial Examples Require a Complex Defense: Identifying Over-optimized Adversarial Examples with IQR-based Logit Thresholding"
collection: publications
date: 2019-01-01
permalink: 19-ijcnn
venue: '2019 The International Joint Conference on Neural Networks (IJCNN) <br /> Main track, oral presentation'
---
**Utku Ozbulak**, Arnout Van Messem, Wesley De Neve <br /> [Download paper](https://arxiv.org/abs/1907.12744) <br />

**Abstract**

Detecting adversarial examples currently stands as one of the biggest challenges in the field of deep learning. Adversarial attacks, which produce adversarial examples, increase the prediction likelihood of a target class for a particular data point. During this process, the adversarial example can be further optimized, even when it has already been wrongly classified with 100% confidence, thus making the adversarial example even more difficult to detect. For this kind of adversarial examples, which we refer to as over-optimized adversarial examples, we discovered that the logits of the model provide solid clues on whether the data point at hand is adversarial or genuine. In this context, we first discuss the masking effect of the softmax function for the prediction made and explain why the logits of the model are more useful in detecting over-optimized adversarial examples. To identify this type of adversarial examples in practice, we propose a non-parametric and computationally efficient method which relies on interquartile range, with this method becoming more effective as the image resolution increases. We support our observations throughout the paper with detailed experiments for different datasets (MNIST, CIFAR-10, and ImageNet) and several architectures.
