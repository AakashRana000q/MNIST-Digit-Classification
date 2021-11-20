# MNIST-Digit-Classification
This project involves builing ML model to solve the well known problem of MNIST Digit Classification.

All of the code is in Python and I have used PyTorch framework in order to build the model which is a 
Convolutinal Neural Network.

# Dataset 
The MNIST Digit classification dataset is divided into two parts train set and test set.  The train set consists of 60,000 small 28x28 pixel grayscale images while 
the test set contains 10,000 images with same dimensions.  The image below represents some instances of images. For preprocessing, I have only normalized the images with mean 
and standard deviation. There are a total of 10 classes (ten digits from zero to nine)

Below is a examples of some instances of images. 

# Convolutional Neural Network
The network is relatively simpler with two convolutional layers. The activation function is ReLU which provides non linearity. I have used only one max pooling layer after 
the first convolutional layer. The goal of model is to minimize the cross entropy loss and in turn achieve a higher classification accuracy.

# Result
After training for 40 epochs, at the end I achieved an accuracy of 99.83% while the test accuracy is around 98.34%.
