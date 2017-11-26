# Convolution Neural Networks for Image Recognition
This repository contains the assignment solution for the Stanford course [Convolution Neural Networks for visual recognition](http://cs231n.stanford.edu/). 
For a beginner starting with neural networks and deep learning should definitely implement these assignments. It will give you a great 'feel' about some of the intricate concepts of neural nets like BackProp for example. 
## Assignment 1 
1. [knn.ipynb](Assignment1/knn.ipynb): contains an implementation of the nearest neighbour algorithm. One of the first algorithm in machine learning. It is later followed up by the generalised K nearest neighbour algorithm
1. [svm.ipynb](Assignment1/svm.ipynb): takes you through the svm classifier </br> 
1. [softmax.ipynb](Assignment1/softmax.ipynb): This assignment is more oriented towards softmax classifier. The advantage of the softmax classifier is a smooth and differentiable which is why it is advantageous over SVM
1. [two\_layer\_net.ipynb](Assignment1/two_layer_net.ipynb): This assignment walks through building a neural network(two layered) to build your initial classifier
1. [features.ipynb](Assignment1/features.ipynb): This assignment asks you to directly input the useful data to the network like the image histogram which improves the accuracy of the network

## Assignment 2 
1. [FullyConnectedNets.ipynb](Assignment2/FullyConnectedNets.ipynb): This assignment asks to create a general **n** layered neural network. This taks is slighly more difficult than the previous two layered model because of an abstraction associated with it. If you want to learn backprop algorithm thoroughly, this is the part of the assignment that you should do
1. [BatchNormalization.ipynb](Assignment2/BatchNormalization.ipynb): This assignment has one single objective i.e to implement a batch normalization in each and every one of the layers in neural networks. It does look easy but believe me it is not! batchnormalization essentially makes the mean zero and variance one before an input is given to each layer of the network. This simple idea makes the backprop calculations very messy(if not difficult)
1. [Dropout.ipynb](Assignment2/Dropout.ipynb): Implements a dropout layer, accuracy slightly increases(though i wouldn't recommend it)
1. [ConvolutionalNetworks.ipynb](Assignment2/ConvolutionalNetworks.ipynb): This is the main point of the course. It essentially asks you to implement the convolutional networks(Observe the change in accuracy from the initial deep networks that were created) 

## Assignment 3 
1. [RNN\_Captioning.ipynb](Assignment3/RNN_Captioning.ipynb): Helps understand RNNs(loosely speaking they are temporal neural nets) and implement a simple image captioning. Works well but not ground breaking results. 
1. [LSTM\_Captioning.ipynb](Assignment3/LSTM\_Captioning.ipynb): Slightly different versions of RNNs(used more extensively in the community) gives slightly better results than RNN implementation.   
