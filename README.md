# mnist-data
The MNIST data is a database of handwritten digits.

>The dataset can be downloaded from here. [MNIST](http://yann.lecun.com/exdb/mnist/)


## Models built
various types of Nural nets have been experimented with this dataset.

Models Built using the following models:
+ Artificial Neural Networks
    + Implemented from scratch
    + Implemeted using Keras
+ Convolutional Neural Networks
    + Implemented using Keras
+ Transfer Learning
    + Model built using VGG16 weights


## Models Comparision
Model | Train Accuracy | Test Accuracy
------ | -------------- | ----------
ANN_from_scratch | 99.82 % | 97.66 %
ANN (keras) | 98.83 % | 96.53 %
CNN (keras) | 99.16 % | 98.76 %
VGG16 (keras) | 98.80 % | 96.29 %


> **Note** : The dataset that has been used in this dataset has been loaded from the mnist package. It is also available in keras.datasets.mnist. 
