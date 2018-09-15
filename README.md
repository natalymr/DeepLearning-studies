# DeepLearning-studies

This repo contains homework for DL course

## First Task
Implement different optimization methods wihout using autograd or torch.optim. You are only allowed to use pytorch as yur numeric computation framework. The only exception is visualize function


The loss you should try to minimize is the Hinge Loss:
$L = \frac{1}{N} \sum max(0, 1 - y_i \cdot w^T x_i)$


Find an optimal learning rate for gradient descent for given batch size.

* Implement gradient descent.
* Implement gradient descent with momentum.
* Nesterov's accelerated gradient:
* Adam algorithm

## Second Task

* Implement simple fully-convolutional neural architecture for classification. Make sure it is small enought to run on your home machine.
* Provide dataset visulization.
* Provide train/test split and validation
