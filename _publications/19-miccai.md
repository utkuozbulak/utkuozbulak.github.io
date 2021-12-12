---
title: "Impact of Adversarial Examples on Deep Learning Models for Biomedical Image Segmentation"
collection: publications
date: 2019-10-01
permalink: 19-miccai
venue: '2019 The International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) <br /> Main track, poster presentation'
---
**Utku Ozbulak**, Arnout Van Messem, Wesley De Neve <br /> [Download paper](https://arxiv.org/abs/1907.13124) <br /> [Download code](https://github.com/utkuozbulak/adaptive-segmentation-mask-attack)

**Abstract**
Deep learning models, which are increasingly being used in the field of medical image analysis, come with a major security risk, namely, their vulnerability to adversarial examples. Adversarial examples are carefully crafted samples that force machine learning models to make mistakes during testing time. These malicious samples have been shown to be highly effective in misguiding classification tasks. However, research on the influence of adversarial examples on segmentation is significantly lacking. Given that a large portion of medical imaging problems are effectively segmentation problems, we analyze the impact of adversarial examples on deep learning-based image segmentation models. Specifically, we expose the vulnerability of these models to adversarial examples by proposing the Adaptive Segmentation Mask Attack (ASMA). This novel algorithm makes it possible to craft targeted adversarial examples that come with (1) high intersection-over-union rates between the target adversarial mask and the prediction and (2) with perturbation that is, for the most part, invisible to the bare eye. We lay out experimental and visual evidence by showing results obtained for the ISIC skin lesion segmentation challenge and the problem of glaucoma optic disc segmentation. An implementation of this algorithm and additional examples can be found at [https://github.com/utkuozbulak/adaptive-segmentation-mask-attack](https://github.com/utkuozbulak/adaptive-segmentation-mask-attack).
