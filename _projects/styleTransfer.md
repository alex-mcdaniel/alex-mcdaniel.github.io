---
layout: page
title: Style Transfer in PyTorch
description: A style transfer application built in PyTorch (ML/AI, Neural Networks, Transfer Learning, Python, PyTorch)
img: assets/img/styleTransfer_creek.png
importance: 2
category: fun
---


Style transfer in machine learning is a technique that allows the artistic style of one image to be applied to another image. It involves extracting the style features from one image (e.g. colors, textures, patterns) and applying them to the content of another image while preserving its original structure. This process is often achieved using deep neural networks to separate and recombine the content and style representations of images.


In this project I use a pretrained convolutional neural network to create a style transfer application in PyTorch. The code is bassed on <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf">Gatys et al.</a> and the <a href="https://www.udemy.com/course/pytorch-for-deep-learning-and-computer-vision/">PyTorch for Deep Learning and Computer Vision</a> Udemy course from Slim et al. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/styleTransfer_creek.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tsyle_transfer.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>
