# Neural Network with NumPy
This project implements a neural network from scratch using NumPy to classify synthetic data.

## Project summary

This project is composed by the following main components:

- **Data generation**: Synthetic data is created using `make_gaussian_quantiles` from `sklearn.datasets` to generate a binary classificaton data set.
- **Activation functions**: Implementation of functions **ReLU** and **Sigmoid**, along with its derivatives.
- **Loss function**: The **Mean Square Error (MSE)** is used as a way to evaluate the loss.
- **Neural network training**: Implementation of **Backpropagation** algorithm and the **Descending Gradient**.
- **Visualization**: Graphs are generated using `matplotlib` to represent the data and the results of the training.
