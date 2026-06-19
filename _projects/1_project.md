---
title: Image Enhancement using Metaheuristic Algorithms
description: Master's dissertation project on image enhancement, contrast enhancement, image fusion, brightness preservation, unsharp masking, and multilevel thresholding using metaheuristic optimization algorithms.
img: assets/img/projects/image-enhancement/cover.jpg
importance: 1
category: research
related_publications: true
---




This project was part of my **Master's dissertation**, focusing on the use of **metaheuristic optimization algorithms for digital image enhancement**. The main objective was to improve image contrast, brightness preservation, edge visibility, sharpness, and overall perceptual quality by automatically optimizing image enhancement parameters.

The work explored several nature-inspired and swarm-intelligence-based algorithms, including **Cuckoo Search**, **Modified Cuckoo Search**, **Social Spider Optimization**, **Fireworks Algorithm**, and **Harmony Search**. These algorithms were applied to contrast enhancement, image fusion, multiscale adaptive smoothing-based unsharp masking, and multilevel image thresholding.

## Project Overview

Image enhancement is an important preprocessing step in computer vision, medical imaging, remote sensing, industrial inspection, document analysis, and pattern recognition. In many real-world images, important visual information may be hidden because of poor contrast, low brightness, uneven illumination, noise, or loss of sharpness.

Traditional enhancement methods often require manual parameter tuning. They may also suffer from over-enhancement, brightness distortion, saturation artefacts, or loss of fine details. In this project, image enhancement was formulated as an **optimization problem**, where metaheuristic algorithms search for the best transformation parameters to enhance image quality automatically.

The project focused on:

* Automatic contrast enhancement
* Brightness preservation
* Image fusion-based enhancement
* Edge and detail enhancement
* Multiscale adaptive smoothing
* Unsharp masking
* Multilevel image thresholding
* Optimization-based objective function design
* Visual and quantitative evaluation of enhanced images

## Motivation

The motivation behind this work was to investigate how nature-inspired optimization methods can improve image enhancement performance. Metaheuristic algorithms are useful for this task because they can search complex, nonlinear, and multimodal solution spaces without requiring gradient information.

In image enhancement, the best visual result often depends on multiple competing objectives. For example, increasing contrast may reduce brightness preservation, while sharpening may introduce artefacts. Therefore, optimization-based enhancement methods can provide a flexible way to balance contrast, brightness, sharpness, and structural detail.

## Methodology

The project investigated multiple optimization-driven image enhancement strategies.

### Modified Cuckoo Search-Based Image Enhancement

A modified cuckoo search algorithm was used to identify optimal image enhancement parameters automatically. The goal was to improve image contrast and visual appearance while preserving important image details.

Cuckoo Search is inspired by the brood parasitic behaviour of cuckoo birds and uses Lévy flight-based search to explore the solution space. In this project, the algorithm was adapted for image enhancement by optimizing transformation parameters according to an image quality objective function.

<p>
  <a href="https://link.springer.com/chapter/10.1007/978-81-322-2695-6_53" target="_blank" rel="noopener noreferrer">
    View paper: Modified Cuckoo Search-Based Image Enhancement
  </a>
</p>

### Social Spider Optimized Image Fusion for Contrast Enhancement and Brightness Preservation

This approach used social spider optimization for image fusion-based contrast enhancement and brightness preservation. The method generated multiple enhanced versions of an input image and fused them to obtain a final output with improved contrast while reducing brightness distortion.
  <div class="col-sm mt-3 mt-md-0">
    <a href="{{ 'assets/img/publication_preview/sso_based_paper.jpg' | relative_url }}">
      {% include figure.liquid loading="eager"
         path="assets/img/publication_preview/sso_based_paper.jpg"
         class="img-fluid rounded z-depth-1" %}
    </a>
  </div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    <a href="{{ 'assets/img/publication_preview/sso_based_paper.jpg' | relative_url }}">
      {% include figure.liquid loading="eager"
         path="assets/img/publication_preview/sso_based_paper.jpg"
         class="img-fluid rounded z-depth-1" %}
    </a>
  </div>

  <div class="col-sm mt-3 mt-md-0">
    <a href="{{ '/assets/img/image-enhancement/sso2.jpg' | relative_url }}">
      {% include figure.liquid loading="eager"
         path="/assets/img/image-enhancement/sso2.jpg"
         class="img-fluid rounded z-depth-1" %}
    </a>
  </div>

  <div class="col-sm mt-3 mt-md-0">
    <a href="{{ '/assets/img/image-enhancement/sso3.jpg' | relative_url }}">
      {% include figure.liquid loading="eager"
         path="/assets/img/image-enhancement/sso3.jpg
         class="img-fluid rounded z-depth-1" %}
    </a>
  </div>
</div>

Social Spider Optimization is inspired by the cooperative behaviour of social spiders. In this enhancement framework, it was used to optimize image fusion parameters so that the final image could maintain a better balance between contrast improvement and brightness preservation.

<p>
  <a href="https://doi.org/10.1016/j.asoc.2016.10.012" target="_blank" rel="noopener noreferrer">
    View paper: A social spider optimized image fusion approach for contrast enhancement and brightness preservation
  </a>
</p>

### Cuckoo Search-Optimized Image Fusion for Contrast and Brightness Balance

This work focused on balancing contrast improvement and brightness preservation using Cuckoo Search-optimized image fusion. The method generated optimized enhanced images emphasizing different visual properties, such as contrast, sharpness, and brightness preservation. These images were then fused to produce a final enhanced image with improved visual quality and a better balance between contrast and brightness.

This approach was important because many enhancement techniques improve contrast at the cost of unnatural brightness changes. The Cuckoo Search-optimized fusion strategy aimed to reduce this problem by combining complementary enhanced images.

<p>
  <a href="https://doi.org/10.1016/j.jksuci.2021.07.008" target="_blank" rel="noopener noreferrer">
    View paper: Contrast and brightness balance in image enhancement using Cuckoo Search-optimized image fusion
  </a>
</p>

### Cuckoo Search and Multiscale Adaptive Smoothing-Based Unsharp Masking

This method combined Cuckoo Search optimization with multiscale adaptive smoothing-based unsharp masking. The aim was to improve contrast and sharpness while reducing over-sharpening, halo effects, and saturation artefacts.

Unsharp masking is widely used for edge and detail enhancement, but its performance depends strongly on parameter selection. In this work, Cuckoo Search was used to optimize the enhancement process, while multiscale adaptive smoothing helped preserve relevant structures and suppress undesirable artefacts.

<p>
  <a href="https://doi.org/10.4018/IJAMC.2019070108" target="_blank" rel="noopener noreferrer">
    View paper: A Fusion of Cuckoo Search and Multiscale Adaptive Smoothing Based Unsharp Masking for Image Enhancement
  </a>
</p>

### Fireworks and Harmony Search for Multilevel Image Thresholding

A hybrid Fireworks and Harmony Search algorithm was studied for multilevel image thresholding. The method focused on selecting optimal thresholds for image segmentation and enhancement.

Multilevel thresholding is useful for separating image regions based on intensity values, but selecting optimal thresholds can become computationally expensive as the number of thresholds increases. The hybrid method combined exploration and exploitation capabilities from Fireworks Algorithm and Harmony Search to improve threshold selection.

<p>
  <a href="https://researchportal.port.ac.uk/en/publications/a-hybrid-of-fireworks-and-harmony-search-algorithm-for-multilevel/" target="_blank" rel="noopener noreferrer">
    View paper: A Hybrid of Fireworks and Harmony Search Algorithm for Multilevel Image Thresholding
  </a>
</p>

## Example Results

Add your own result images in this folder:

```text
assets/img/projects/image-enhancement/
```

Recommended image names:

```text
cover.jpg
original-image.jpg
enhanced-cuckoo-search.jpg
enhanced-social-spider.jpg
cuckoo-fusion-balance.jpg
enhanced-unsharp-masking.jpg
thresholding-result.jpg
comparison-results.jpg
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/original-image.jpg" title="Original low-contrast image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/enhanced-cuckoo-search.jpg" title="Enhanced image using modified cuckoo search" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/enhanced-social-spider.jpg" title="Enhanced image using social spider optimization" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Example visual comparison between the original image and enhanced outputs generated using metaheuristic optimization methods.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/cuckoo-fusion-balance.jpg" title="Cuckoo Search-optimized image fusion result for contrast and brightness balance" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Example result from Cuckoo Search-optimized image fusion, designed to balance contrast enhancement and brightness preservation.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/enhanced-unsharp-masking.jpg" title="Cuckoo Search and multiscale adaptive smoothing-based unsharp masking result" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/image-enhancement/thresholding-result.jpg" title="Multilevel thresholding result using hybrid Fireworks and Harmony Search" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Enhancement and segmentation examples based on optimization-driven image processing methods.
</div>

## Key Contributions

* Formulated image enhancement as an optimization problem.
* Applied Modified Cuckoo Search for automatic image enhancement.
* Used Social Spider Optimization for image fusion-based contrast enhancement and brightness preservation.
* Investigated Cuckoo Search-optimized image fusion for balancing contrast and brightness.
* Combined Cuckoo Search with multiscale adaptive smoothing-based unsharp masking for sharpness and detail enhancement.
* Explored hybrid Fireworks and Harmony Search for multilevel image thresholding.
* Compared enhancement outputs using visual inspection and quantitative image quality measures.
* Demonstrated the usefulness of metaheuristic optimization for image processing applications.

## Skills and Tools Used

* Digital Image Processing
* Metaheuristic Optimization
* Cuckoo Search Algorithm
* Modified Cuckoo Search
* Social Spider Optimization
* Fireworks Algorithm
* Harmony Search Algorithm
* Image Fusion
* Contrast Enhancement
* Brightness Preservation
* Unsharp Masking
* Multilevel Thresholding
* MATLAB / Python-based experimentation

## Related Publications

1. **Modified Cuckoo Search-Based Image Enhancement**
   Lalit Maurya, Prasant Kumar Mahapatra, G. Saini
   Proceedings of the 4th International Conference on Frontiers in Intelligent Computing: Theory and Applications, 2015. <a href="https://link.springer.com/chapter/10.1007/978-81-322-2695-6_53" target="_blank" rel="noopener noreferrer">https://link.springer.com/chapter/10.1007/978-81-322-2695-6_53</a>

2. **A social spider optimized image fusion approach for contrast enhancement and brightness preservation**
   Lalit Maurya, Prasant Kumar Mahapatra, Amod Kumar
   Applied Soft Computing, Volume 52, Pages 575–592, 2017. <a href="https://doi.org/10.1016/j.asoc.2016.10.012" target="_blank" rel="noopener noreferrer">https://doi.org/10.1016/j.asoc.2016.10.012</a>

3. **Contrast and brightness balance in image enhancement using Cuckoo Search-optimized image fusion**
   Lalit Maurya, Viney Lohchab, Prasant Kumar Mahapatra, János Abonyi
   Journal of King Saud University - Computer and Information Sciences, Volume 34, Issue 9, Pages 7247–7258, 2022. <a href="https://doi.org/10.1016/j.jksuci.2021.07.008" target="_blank" rel="noopener noreferrer">https://doi.org/10.1016/j.jksuci.2021.07.008</a>

4. **A Fusion of Cuckoo Search and Multiscale Adaptive Smoothing Based Unsharp Masking for Image Enhancement**
   Lalit Maurya, Prasant Kumar Mahapatra, Amod Kumar
   International Journal of Applied Metaheuristic Computing, 10(3), 151–174, 2019. <a href="https://doi.org/10.4018/IJAMC.2019070108" target="_blank" rel="noopener noreferrer">https://doi.org/10.4018/IJAMC.2019070108</a>

5. **A Hybrid of Fireworks and Harmony Search Algorithm for Multilevel Image Thresholding**
   Shivali, Lalit Maurya, Ekta Sharma, Prasant Mahapatra, Amit Doegar
   Advanced Computing and Communication Technologies. <a href="https://researchportal.port.ac.uk/en/publications/a-hybrid-of-fireworks-and-harmony-search-algorithm-for-multilevel/" target="_blank" rel="noopener noreferrer">View publication page</a>

## Dissertation Context

This project formed part of my **Master's dissertation**, where I investigated how nature-inspired optimization algorithms can be used to improve image enhancement performance. The work contributed to my early research direction in optimization-based image processing and later supported my research publications in metaheuristic computing, contrast enhancement, image fusion, and image thresholding.
