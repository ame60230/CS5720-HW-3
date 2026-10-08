# CS5720-HW-3
CS5720 Neural Network and Deep Learning - Home Assignment 3

Aziz Erdogan  
CS5720 Neural Network and Deep Learning  
Fall 2026

##Overview

This assignment covers CNN concepts, convolution, representation learning, and transfer learning.

##Part I - Short Answer

Question 1 covers calculating convolution output size using filter size, stride, and padding.

Question 2 discusses AlexNet, VGGNet, GoogLeNet, and ResNet.

Question 3 covers representation learning, transfer learning, freezing layers, and fine-tuning.

##Part II - Programming

###Question 1

Implemented 2D convolution from scratch using NumPy without using a built-in convolution function. The filter is manually moved across the input matrix to create the output feature map.

###Question 2

Used a pretrained MobileNetV2 model with cat and dog images from CIFAR-10. I compared a frozen feature extractor with a fine-tuned model.

The frozen model reached about 84.95% test accuracy, while the fine-tuned model reached about 85.85%. I also compared their trainable parameters, training time, and training loss.
