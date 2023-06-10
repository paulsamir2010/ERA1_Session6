# ERA1_Session6

## Session 6 Assignment of ERA 1 program from TSAI "The School of AI" - Backpropagation and Advanced Architectures

###  Part 2

#### About Part 2 of this Assignment

To create a CNN based model using Batch Normalization and Dropout.

Target is to reach Test/Validation accuracy of 99.4 % within 20 epochs, model parameters to be within 20,000

Dataset = MNIST

Batch size = 128

Optimizer = SGD

Learning rate = 0.01

#### Accuracy - Test/validation

Test accuracy reached 99.43% in 17th epoch. However 99.3% was observed consistently in many other epochs.

Model Parameters useds = 17,214

#### Model Parameters and Architecture

Relu Activation Function used

Batch Normalization and Dropout used.

#### Framework and main libraries used

Framework = Pytorch

Model trained on = Google colab

Main libraries used stated below:

import torch 

import torch.nn as nn 

import torch.nn.functional as F 

import torch.optim as optim 

from torchvision import datasets, transforms 

import matplotlib.pyplot as plt

