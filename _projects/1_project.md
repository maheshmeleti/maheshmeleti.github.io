---
layout: page
title: Brush Stroke Parameterized Style Transfer
description: A brush stoke parameterized representation using beizer curves to represent artistic style
img: assets/img/brush_stroke/Method.png
importance: 1
category: work
giscus_comments: true
---

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/maheshmeleti/brushstroke-parameterized-style-transfer-pytorch">
    <img src="https://img.shields.io/badge/GitHub-Repository-blue?logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/mahesh-meleti/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin" alt="LinkedIn">
  </a>
  <a href="paper/BrushStroke_StyleTransfer.pdf">
    <img src="https://img.shields.io/badge/Project-Paper-blue" alt="Paper">
  </a>
  <a href="paper/final_project_presentation.pdf">
    <img src="https://img.shields.io/badge/Course-Presentation-blue" alt="Presentation">
  </a>
  <a href="https://maheshmeleti.github.io/param-brushstroke/">
    <img src="https://img.shields.io/badge/Project-Website-blue" alt="Project Website">
  </a>
  <a href="https://sites.google.com/view/cpsc8810-2024fall/home">
    <img src="https://img.shields.io/badge/Course-page-blue" alt="course-link">
  </a>
</div>

<div style="margin-top: 10px;"></div>


## Abstract

Computer Vision-based Style Transfer techniques have been used for many years to represent artistic style. However, most contemporary methods have been restricted to the pixel domain; in other words, the style transfer approach has been modifying the image pixels to incorporate artistic style. However, real artistic work is made of brush strokes with different colors on a canvas. Pixel-based approaches are unnatural for representing these images. Hence, this paper discusses a style transfer method that represents the image in the brush stroke domain instead of the RGB domain, which has better visual improvement over pixel-based methods.

## Methodology

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brush_stroke/Method.png" title="Methodology" class="img-fluid rounded z-depth-1" style="width: 70%; height: 70%;" %}
    </div>
</div>


## Results

### Video Result

This is an example post with videos. It supports local video files.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/brush_stroke/road.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true width="100%" %}
    </div>
</div>
<div class="caption">
    This video demonstrates the application of the parameterized brush strokes optimization using content and style transfer.
</div>

### Image Results

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brush_stroke/bridge.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image shows the result of applying the style transfer technique to content image - Golden Gate Bridge and Style image Van Gogh\'s Starry Night. Notice the intricate brush strokes and the overall artistic transformation.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brush_stroke/strokes_zoomed.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Zoomed in view of brush strokes and texture after pixel optimization
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brush_stroke/me.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Style transfer applied on human (It's me in the photo :) 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/brush_stroke/Olive_tree_garden.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The style transfer is applied to Olive garden with stylization using the famous The stone Bench in the Garden of Saint-Paul Hospital by Van Gogh
</div>

## Social and Other Links

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/maheshmeleti/brushstroke-parameterized-style-transfer-pytorch">
    <img src="https://img.shields.io/badge/GitHub-Repository-blue?logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/mahesh-meleti/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin" alt="LinkedIn">
  </a>
  <a href="paper/BrushStroke_StyleTransfer.pdf">
    <img src="https://img.shields.io/badge/Project-Paper-blue" alt="Paper">
  </a>
  <a href="paper/final_project_presentation.pdf">
    <img src="https://img.shields.io/badge/Course-Presentation-blue" alt="Presentation">
  </a>
  <a href="https://maheshmeleti.github.io/param-brushstroke/">
    <img src="https://img.shields.io/badge/Project-Website-blue" alt="Project Website">
  </a>
  <a href="https://sites.google.com/view/cpsc8810-2024fall/home">
    <img src="https://img.shields.io/badge/Course-page-blue" alt="course-link">
  </a>
</div>

## References

@article{kotovenko_cvpr_2021,
    title={Rethinking Style Transfer: From Pixels to Parameterized Brushstrokes},
    author={Dmytro Kotovenko and Matthias Wright and Arthur Heimbrecht and Bj{\"o}rn Ommer},
    journal={CVPR},
    year={2021}
}

## Citation

@misc{meleti2024brushstroke, title={Brush Stroke Parameterized Style Transfer}, author={Uma Maheswara R Meleti}, year={2024}, url={https://github.com/maheshmeleti/brushstroke-parameterized-style-transfer-pytorch}, } -->