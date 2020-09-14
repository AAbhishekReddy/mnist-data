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
+ Recurent Neural Networks
    + Simple RNN
    + Long Short Term Memory (LSTM) RNN


## Models Comparision
Model | Accuracy
------ | ----------
ANN_from_scratch | 97.66 %
ANN (keras) | 96.53 %
CNN (keras) | 98.76 %
VGG16 (keras) | 96.29 %
Simple RNN | 99.8 %
LSTM | 98.8 %

> **Note** : The dataset that has been used in this repo has been loaded from the **mnist** package. It is also available in **keras.datasets.mnist**. 
