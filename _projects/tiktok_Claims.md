---
layout: page
title: Style Transfer in PyTorch
description: A style transfer application built in PyTorch (ML/AI, Neural Networks, Transfer Learning, Python, PyTorch)
img: assets/img/styleTransfer_creek.png
importance: 2
category: fun
---


Style transfer in machine learning is a technique that allows the artistic style of one image to be applied to another image. It involves extracting the style features from one image (e.g. colors, textures, patterns) and applying them to the content of another image while preserving its original structure. This process is often achieved using deep neural networks to separate and recombine the content and style representations of images. 

In this project I use a pretrained convolutional neural network to create a style transfer application in PyTorch. The notebook for this project can be found as a <a href="StyleTransfer_in_PyTorch.html">static wbepage here</a>. The code is bassed on <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf">Gatys et al.</a> and the <a href="https://www.udemy.com/course/pytorch-for-deep-learning-and-computer-vision/">PyTorch for Deep Learning and Computer Vision</a> Udemy course from Slim et al. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/styleTransfer_creek.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Content image (left) is a phtoo of one of the many waterfalls in the Clemson, SC area. The style image (middle) is Edvard Munch's "The Scream", and on the right we have the final composite image.
</div>

Below is a gif showing some of the iterative steps of the style transfer.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/style_transfer.gif" title="style_tranfer.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>
