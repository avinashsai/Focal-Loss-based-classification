# Focal-Loss-based-classification
## Image Classification
Image Classification is performed on CIFAR-10 dataset with both Categorical Cross Entropy Loss(CCE) and Focal Loss(FL). Focal Loss showed better performance when compared to CCE. The training loss is much less for FL in each epoch compared to CCE. This is primarly because FL imposes heavy loss when correct samples are classified wrong. 

Focal Loss is perfomed with two sets of values: 

1. alpha = 0.25,gamma=2.

![alt text](https://raw.githubusercontent.com/avinashsai/Focal-Loss-based-classification/master/Image%20Classification/accuracy_gamma2_alpha0.25.png)
