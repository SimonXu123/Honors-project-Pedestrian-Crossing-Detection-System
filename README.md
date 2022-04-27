# Honors-project
## Project background

For many people living with visual impairments or blindness, assistive navigation is essential to
build self-reliance and improve their quality of life. The traditional aids to help the blind or visually impaired are white cane and guide dog. However, these tools can not guarantee safety, especially
when a person crosses a road via the pedestrian crosswalk. The traditional tools can only alert the user when they are close to obstacles, not correctly guiding them to walk in the appropriate area. Given this problem, there is no existing tool to guide visually impaired people at the pedestrian crossings safely.

## Project outline

This project aims to develop a vision system for detecting the pedestrian crossing lane using deep networks, including Fully Convolutional Network (FCN) and Semantic Segmentation Network (SegNet). FCN uses a convolutional neural network to transform image pixels into pixel categories. SegNet is a semantic pixel-wise segmentation based on a convolutional encoder-decoder. Both methods can utilize low-resolution features and classify the different regions of a color input image. The network design and construction use Deep Learning Toolbox and Image Processing Toolbox based on MATLAB version R2020A.

## Project outline

In this project, a large-scale dataset of pedestrian crossing lane photos and its related annotated
ground truths were fed into two different neural networks (FCN and SegNet). The FCN system
achieved an accuracy of 84.1% and took 1072 minutes to process 1975 input images, while the
SegNet system took 672 minutes and its accuracy is 83.6%. The developed method can be applied to improve assistive navigation technologies, and the developed algorithms can also be used in autonomous vehicles and intelligent robots.
