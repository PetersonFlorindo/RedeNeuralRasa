# Shallow Neural Network from Scratch

This repository contains a simple and educational implementation of a shallow neural network built from scratch in Python.

The project was developed to demonstrate, in a clear and didactic way, how a neural network works internally, without relying on classic deep learning libraries such as TensorFlow, Keras or PyTorch.

## Objective

Build a shallow neural network from scratch to explain the main steps behind neural network training, including weight initialization, forward propagation, error calculation and backpropagation.

The model is applied to a housing price prediction dataset, using normalized input variables to estimate house prices.

## Dataset

The project uses a housing price dataset with numerical and categorical variables related to property characteristics.

The target variable is:

```text
price
```

Categorical variables are converted into dummy variables before training.

## Methodology

The notebook implements the following steps:

* Data loading
* Categorical variable encoding with dummy variables
* Feature and target separation
* Min-max normalization
* Train-test split
* Manual weight initialization
* Sigmoid activation function
* Forward pass
* Backpropagation
* Weight updates using learning rate
* Training over multiple epochs
* Mean squared error evaluation
* Visualization of training error

## Neural Network Architecture

The implemented network has:

* Input layer based on the number of dataset features
* One hidden layer with 10 neurons
* One output neuron
* Sigmoid activation function
* Mean squared error as the loss function

## Requirements

Install the main dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

Open the notebook:

```bash
jupyter notebook REDE_NEURAL_RASA.ipynb
```

Update the dataset path if necessary:

```python
df = pd.read_csv("Housing.csv")
```

Then run the cells in order to train and evaluate the neural network.

## Output

The notebook generates:

* Training loss curve
* Train vs test error comparison
* Mean squared error on the test set
* Predicted values for the housing price target

## Applications

* Educational introduction to neural networks
* Understanding forward propagation
* Understanding backpropagation
* Demonstrating weight updates
* Teaching the basics of machine learning without high-level libraries
* Simple regression problems

## Notes

This project was created for learning purposes. The goal is not to maximize predictive performance, but to make the internal logic of a neural network easier to understand.

## Authorship

This project was developed by Peterson Oliveira Florindo.

The use, study, adaptation and sharing of this code are allowed, as long as proper credit is given to the author. This project is made available for educational, academic and research purposes.
