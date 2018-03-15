# LeNet-5 CNN  
## Introduction
This repository of LeNet-5 is my first neual network by python. The LeNet-5 implementation of the convolutional neural network is based on deeplearning.ai courses. Thanks!
## Environment
Convolutional Neural Networks are are a special kind of multi-layer neural networks. Like almost every other neural networks they are trained with a version of the back-propagation algorithm. Where they differ is in the architecture.   
Convolutional Neural Networks are designed to recognize visual patterns directly from pixel images with minimal preprocessing.  They can recognize patterns with extreme variability (such as handwritten characters), and with robustness to distortions and simple geometric transformations.  
LeNet-5 is our latest convolutional network designed for handwritten and machine-printed character recognition. 
![LeNet-5](https://github.com/ShamCondor/LeNet-5/blob/master/lenet-5.png)
## Process
Input:32-32 image

C1:5-5-6,stride=1->28-28-6

P1:2-2,stride=2->14-14-6

C2:5-5-16,stride=1->10-10-16

P2:2-2,stride=2->5-5-16

FC3:120

FC4:84

softmax:10
