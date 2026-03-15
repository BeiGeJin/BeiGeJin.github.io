---
layout: page
title: "High-Resolution Source Estimation using a Naturalistic MEG-fMRI Encoding Model"  
description: Advised by Prof. Leila Wehbe, CMU
# img: assets/img/12.jpg
importance: 1
category: RESEARCH
redirect: https://beigejin.github.io/MEG-fMRI-website/
---

Current non-invasive neuroimaging techniques trade off between spatial resolution and temporal resolution. While magnetoencephalography (MEG) can capture rapid neural dynamics and functional magnetic resonance imaging (fMRI) can spatially localize brain activity, a unified picture that preserves both high resolutions remains an unsolved challenge with existing source localization or MEG-fMRI fusion methods, especially for single-trial naturalistic data.  

We collected whole-head MEG when subjects listened passively to more than seven hours of narrative stories, using the same stimuli in an open fMRI dataset (LeBel et al., 2023). We developed a transformer-based encoding model that combines the MEG and fMRI from these two naturalistic speech comprehension experiments to estimate latent cortical source responses with high spatiotemporal resolution. Our model is trained to predict MEG and fMRI from multiple subjects simultaneously, with a latent layer that represents our estimates of reconstructed cortical sources. 

Our model predicts MEG better than the common standard of single-modality encoding models, and it also yields source estimates with higher spatial and temporal fidelity than classic minimum-norm solutions in simulation experiments. We validated the estimated latent sources by showing its strong generalizability across unseen subjects and modalities. Estimated activity in our source space predict electrocorticography (ECoG) better than an ECoG-trained encoding model in an entirely new dataset. By integrating the power of large naturalistic experiments, MEG, fMRI, and encoding models, we propose a practical route towards millisecond-and-millimeter brain mapping.

[Paper](https://arxiv.org/abs/2510.09415)

Poster (presented at SNL2025):

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe src="{{ '/assets/pdf/beige_MEGfMRI_poster.pdf' | relative_url }}" width="100%" height="500px" style="border: none;"></iframe>
    </div>
</div>