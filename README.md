# Image Style Transfer Using Convolutional Neural Networks

Implemented based on this [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)


 - Load in a pre-trained VGG Net
 - Freeze the weights in selected layers, so that the model can be used as a fixed feature extractor
 - Load in content and style images
 - Extract features from different layers of our model
 - Complete a function to calculate the gram matrix of a given convolution layer
 - Define the content, style, and total loss for iteratively updating a target image
