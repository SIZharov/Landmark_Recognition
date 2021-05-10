# Landmark recognition task

This repository contains a CNN that classifies landmarks. Classifier use pre-trained on the ImageNet database convolutional neural network VGG19 as a backbone. Network was trained on "Paris 6K" dataset and predicts 11 classes whith 85% test accuracy. To download dataset and get more information about data [look here.](https://www.robots.ox.ac.uk/~vgg/data/parisbuildings/) 

![](git_decore/Landmarks.jpg)

## Requirements
+ TensorFlow>=2.4.1
+ Keras>=2.4.0

## Results
Evaluation of precision (blue) and recall (orange) by class

![](git_decore/bar_plot.png)
