Handwritten Digit Recognition
Deep Learning Project
Libraries, Tools used:

Python programming
Deep learning (Convolutional Neural Networks) with Keras library
Tensorflow and Keras libraries
To implement a handwritten digit recognition app which uses the image of a digit and recognizes the digit present in the image. This will be done using Convolutional Neural Networks which is a type of deep neural network.

Steps involved:
Import the libraries and load the dataset into training and test data
Preprocess the data
Create the model
Train the model using training data
Evaluate the model using testing data
Dataset used: The MNIST dataset
The MNIST dataset contains 60,000 training images of handwritten digits from zero to nine and 10,000 images for testing. So, the MNIST dataset has 10 different classes. The handwritten digits images are represented as a 28×28 matrix where each cell contains grayscale pixel value.

The Model
A CNN model generally consists of convolutional and pooling layers. It works better for data that are represented as grid structures, this is the reason why CNN works well for image classification problems. The dropout layer is used to deactivate some of the neurons and while training, it reduces offer fitting of the model. We will then compile the model with the Adadelta optimizer.

Convolutional neural network
A convolutional neural network, or CNN, is a deep learning neural network designed for processing structured arrays of data such as images. They are very good at picking up on patterns in the input image, such as lines, gradients, circles, or even eyes and faces. It is this property that makes convolutional neural networks so powerful for computer vision.

Convolutional neural networks contain many convolutional layers stacked on top of each other, each one capable of recognizing more sophisticated shapes. With three or four convolutional layers it is possible to recognize handwritten digits and with 25 layers it is possible to distinguish human faces.

The usage of convolutional layers in a convolutional neural network mirrors the structure of the human visual cortex, where a series of layers process an incoming image and identify progressively more complex features.