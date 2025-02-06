## MNIST-NN
This repository contains code that trains a three-layer neural network on the MNIST dataset, a widely used benchmark for handwritten digit recognition.

## Description
This project implements a simple deep neural network using Python and NumPy. The network consists of an input layer, a hidden layer, and an output layer. The main functionalities include:

  **Initializing** the network with user-defined parameters (number of nodes, learning rate).
  **Training** the network using backpropagation and gradient descent.
  **Querying** the network to predict handwritten digits from the MNIST dataset.
  **Testing** performance to evaluate accuracy on unseen data.
  
## Network Structure
Input Layer: 784 nodes (corresponding to 28×28 pixel images).
Hidden Layer: Customizable number of nodes.
Output Layer: 10 nodes (one for each digit from 0-9).
Activation Function: Sigmoid (logistic function).

## Training Process
The network is trained using the MNIST dataset, where each image is converted into a 784-element vector and normalized. The training loop consists of:

Forward Pass: Compute weighted inputs and activations for each layer.
Backward Pass (Backpropagation): Calculate errors and adjust weights using gradient descent.
Updating Weights: Apply learning rate to optimize weight adjustments.
Testing: Evaluate performance on test data after each epoch.

## Implementation
The model is trained and tested with different learning rates over multiple epochs, tracking performance dynamically to find the optimum learning rate and number of epochs.

## Future Improvements
Implement different activation functions.
Experiment with another different sizes of hidden layer.
Experiment with deeper architectures (multiple hidden layers).
Improve running time.

## Inspiration, code snippets, etc.
Tariq Rashid's "Make Your Own Neural Network"
