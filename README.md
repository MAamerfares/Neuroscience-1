# Neural Network from Scratch

## Overview
This project implements a simple feedforward neural network with one hidden layer using PyTorch. The network takes a 2D input, processes it through a hidden layer with a hyperbolic tangent activation function, and produces a 2D output.

## Features
- Implemented forward propagation manually.
- Used hyperbolic tangent (tanh) as an activation function.
- Initialized weights randomly within a range.
- Computed the Mean Squared Error (MSE) loss function.

## Code Explanation
- *Input Values:* The network takes an input tensor of shape (1,2).
- *Weights & Biases:* Initialized randomly within the range [-0.5, 0.5].
- *Activation Function:* The tanh function is used to introduce non-linearity.
- *Loss Function:* Mean Squared Error (MSE) is used to evaluate performance.

## Future Improvements
- Implement backpropagation to update weights using gradient descent.
- Expand the model to support more complex datasets.
- Convert the 2D pose estimation project to a 3D model.
