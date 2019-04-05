
# Classifying CIFAR-10 Using CNN

## Introduction

In this assignment, I was tasked with creating a classifier for making
predictions on the CIFAR-10 dataset. Given an initial model, I was tasked
with making significant improvements to the model.

## Methods

In my solution, I designed my model to be a barebones version
of the ResNet architecture, where I used residual blocks to pass information
through the network. A supposed benefit would be preservation of past
information and propagation of gradients to prevent vanishing gradients.

I also made use of data augmentation to increase outputs. This was done
before I implemented the final model architecture, but still helped to achieve
results with a validation accuracy at least 10% higher than without.

## Results

To run the code, I ran the code using Google Colab in the Python 3 GPU
environment. The notebook is also available in this directory along
with a viewable HTML document. At the end, the training accuracy was
around 83%, which was far better than the initial accuracy, which was
closer to 60% initially. With more resources, I would have liked to explored
using a fuller version of the architecture. Furthermore, I may have tried
pretraining on a problem such as ImageNet, which is similar in nature to
this problem.

