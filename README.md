## Training and Visualisation of Feedforward Neural Networks

### Introduction

### Description

In this project we will investigate deep neural networks to solve the task of letter and digit classification and visualise the features they learend. We will use the 'balanced' version the EMNIST dataset containing 28x28-pixel grayscale images of handwritten digits and letters in 47 mutually exclusive classes. More details can be found in this paper. The dataset is an drop-in extension of the famous MNIST dataset of handwritten digits that was and still is commonly used as a first test or 'sanity check' for new classification algorithms. 
The first part of the project will introduce you to some basics of image classification using deep feedforward neural networks. The second part of the project uses standard and not-so-standard ways [1] of visualising learned features in deep neural networks. The results can be quite esthetically appealing, for example visualising the preferred input of hidden units deep inside the Residual Network ResNet50:

[1] D. Erhan, Y. Bengio, A. Courville, and P. Vincent. Visualizing higher-layer features of a deep network. Technical Report 1341, University of Montreal, Jun 2009. https://pdfs.semanticscholar.org/65d9/94fb778a8d9e0f632659fb33a082949a50d3.pdf

### Prerequisites

You should have a running installation of tensorflow 2 which includes the keras package as a tensorflow 2 module. Feel free to gain inspiration for model architecture and training procedures from the Keras example directory for your implementations. 
Important: Since we are using tensorflow 2 you have to import Keras (functions) via tensorflow, i.e.
from keras.models import Sequential
from tensorflow.keras.models import Sequential
You should know the concepts "multilayer perceptron", "stochastic gradient descent with minibatches", "convolutional neural network", "training and validation data", "overfitting" and "backpropagation".

### What you will learn

You will learn how to define feedforward neural networks in keras and fit them to data.
You will get in contact with concepts discussed in the lecture, like "regularization", "batch normalization" and "convolutional networks".
You will gain some experience on how to visualise the learned features in deep neural networks to get some intuition what they actually "learn". 
You will learn to be more patient :) Some fits may take your computer quite a bit of time; run them over night (or on an external server). If you have access to a GPU you can also use the gpu support of tensorflow 2 to speed up simulations.
