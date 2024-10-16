---
title: "Real-time Acquisition and Reconstruction of Dynamic Volumes with Neural Structured Illumination"
collection: publications
permalink: /publication/dynamic_smoke
excerpt: '**Yixin Zeng\***, Zoubin Bi*(*contribute equally), Mingrui Yin, Xiang Feng, Kun Zhou, Hongzhi Wu'
date: 2021-08-30
venue: 'CVPR 2024'
paperurl: 'https://svbrdf.github.io/publications/realtimedynamic/realtimedynamic.pdf'
code: 'https://github.com/zyx45889/RealtimeDynamic'
video: 'https://www.youtube.com/watch?v=XoTYTGSueh4'
project_page: 'https://svbrdf.github.io/publications/realtimedynamic/project.html'
year: '2024'
first_author: 'yes'
teaser: 'http://zyx45889.github.io/images/publications/neuralSL.jpg'
---

<b>Abstract:</b>

Facial structure editing of portrait images is challenging given the facial variety, the lack of ground-truth, the necessity of jointly adjusting color and shape, and the requirement of no visual artifacts. In this paper, we investigate how to perform chin editing as a case study of editing facial structures. We present a novel method that can automatically remove the double chin effect in portrait images. Our core idea is to train a fine classification boundary in the latent space of the portrait images. This can be used to edit the chin appearance by manipulating the latent code of the input portrait image while preserving the original portrait features. To achieve such a fine separation boundary, we employ a carefully designed training stage based on latent codes of paired synthetic images with and without a double chin. In the testing stage, our method can automatically handle portrait images with only a refinement to subtle misalignment before and after double chin editing. Our model enables alteration to the neck region of the input portrait image while keeping other regions unchanged, and guarantees the rationality of neck structure and the consistency of facial characteristics. To the best of our knowledge, this presents the first effort towards an effective application for editing double chins. We validate the efficacy and efficiency of our approach through extensive experiments and user studies.
