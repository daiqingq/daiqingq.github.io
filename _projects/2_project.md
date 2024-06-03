---
layout: page
title: Introducing New Objects into Scenes via Text-guided Image Editing
# description: We receives NSF grant to explore how Generative AI can generate K-12 test questions
img: assets/img/proj/edit.jpeg
importance: 1
category: work
related_publications: false
---

Text-to-image diffusion models have demonstrated their capability to produce a spectrum of diverse, high-fidelity images. Recent studies extend the functionalities of these models to text-guided image manipulation, encompassing a variety of editing contexts such as style transformation and object refinement. Nonetheless, our study unveils a perplexing problem that eluded prevailing text-guided image editing models: the seamless integration of a novel object into a reference background. In this work, we embark on a meticulous exploration of this specific challenge. First we expose the limitations of prior models in this context. 
Correspondingly, we propose a novel approach that customizes the editing process (i.e., the diffusion denoising process) to facilitate the seamless integration of new objects, drawing inspiration from the principles of compositional generation in energy-based models (EBMs). 
And different from prior works on EBMs, where different conditions (prompts) are assumed to be independent to each other in probability decomposition during denoising, in our scenario, old and new prompts are highly related, motivated by which we further consider the correlation between them, leading to better integration of new objects in given images.
Furthermore, to ensure the stability of the editing process, we perform a lightweight optimization over a tiny set of parameters, balancing the preservation of the background with the introduction of new elements. 