# mnist-nn
 Implementing a neural network to classify MNIST digits.

# Objectives
[In previous task](https://github.com/dnlam/mnist) , we have tried to solve the digit recognition problem of MNIST by using linear regression, support vector machine and kernel. 

In this project, we will be using deep neural network to perform the same classification task as in previous sections. We will use PyTorch, a python deep learning framework. Using a framework like PyTorch means you don't have to implement all of the details (like in the earlier problem) and can spend more time thinking through your high level architecture.

# Neural Network basics
Good programmers can use neural nets. Great programmers can make them. In order to obtain more information about Neural Network and how to use them, please visit [here](https://dnlam.github.io/fastblog/2021/06/04/The_Beauty_Of_Neural_Network.html)

# Convolutional Neural Networks
In `part2-mnist/nnet_cnn.py`, we implemented a convolutional neural network with following layers in order:
- A convolutional layer with 32 filters of size 

- A ReLU nonlinearity

- A max pooling layer with size 

- A convolutional layer with 64 filters of size 

- A ReLU nonlinearity

- A max pooling layer with size 

- A flatten layer

- A fully connected layer with 128 neurons

- A dropout layer with drop probability 0.5

- A fully-connected layer with 10 neurons

# Structure of project 
- `part2-nn/neural_nets.py` in which you'll implement your first neural net from scratch
- `part2-mnist/nnet_fc.py` where you'll start using PyTorch to classify MNIST digits
- `part2-twodigit/mlp.py` and `part2-twodigit/conv.py` which are for a new, more difficult version of the MNIST dataset
