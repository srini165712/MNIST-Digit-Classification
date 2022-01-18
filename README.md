# MNIST-Digit-Classification
## A neural network model that uses MNIST dataset of handwritten digits and classifies them accordingly.
### My approach to this problem was by using 2 methods: 
1. Fully Connected Neural Network
2. Convolutional Neural Network

#### Fully Connected Neural Network
First construct a neural network consisting of two fully connected layers and apply this to the digit classification task. This network will ultimately output a probability over the 10 digit(0-9).

![alt_text](https://github.com/srini165712/MNIST-Digit-Classification/blob/main/mnist.png "Fully connected NN Architecture for MNIST Classification")

#### Convolutional Neural Network
Convolutional neural networks (CNN) are well-suited for a variety of tasks in computer vision, and have near-perfect accuracies on the MNIST dataset. First construct model composed of two convolutional layers and pooling layers, followed by fully connected layers mentioned above, and output a probability over the 10 digit(0-9).

![alt_text](https://github.com/srini165712/MNIST-Digit-Classification/blob/main/mnist_model.png "CNN Architecture for MNIST Classification")
