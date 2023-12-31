# ERA1_Session6

## Session 6 Assignment of ERA 1 program from TSAI "The School of AI" - Backpropagation and Advanced Architectures

### Part 1 - Backpropagation in Excel - Derivative Formulas

Simple Neural Network used shown below

![image](https://github.com/paulsamir2010/ERA1_Session6/blob/main/Neural%20Network.jpg)

i1 and i2 are input. a_o1 and o_h2 are output after final sigmoid activation.

It has only 1 hidden layer with two neurons h1 and h2.

Total error E_Total is equal to the sum of E1 and E2

Loss or Error = |Actual - Preducted|

Derivatives of error with respect to each wiight like w5 , w6. w7 etc are calculated, these are used used to finally update the witght as part of backpropagation.



Formulas for Errors, output neurons and hidden neurons are shown below

![image](https://github.com/paulsamir2010/ERA1_Session6/blob/main/Formulas.png)

Derivative calculation are shown below

![image](https://github.com/paulsamir2010/ERA1_Session6/blob/main/Derivatives%201.jpg)



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

![image](https://github.com/paulsamir2010/ERA1_Session6/blob/main/Model%20Parameters.png)

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

