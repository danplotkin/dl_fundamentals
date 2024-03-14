# Fundamentals of Feed-Forward Neural Networks: A Practical Introduction to Deep Learning

## Notebook
[Link to Notebook](https://colab.research.google.com/github/danplotkin/dl_fundamentals/blob/main/FundamentalsofFeedForwardNeuralNetworks.ipynb#scrollTo=8MxrKPhruuee)

## Table of Contents

<details>
   <summary>&nbsp;Show contents</summary>
&nbsp;

>1 - Introduction to Deep Learning

>>A. AL vs ML vs DL: Understanding the Paradigms

>>B. Why Deep Learning is Dominating?

>2 - Introduction to the Artifical Neural Network

>>A. Basic Architecture of an FFN

>>B. Weights and Biases

>>C. Activation Functions

>4 - Training an FFN

>>A. Weight Initialization

>>A. Forward Propagation

>>>I. Forward Pass Algorithm

>>>II. Loss Calculation

>>B. Backpropagation

>>>I. Compute Gradients

>>>II. Gradient Descent

>>C. Mini-Batch Processing

>>D. Epochs

>>E. Minotoring Optimality

>>F. Full Training Loop

>5 - Common Activation Functions

>>A. Rectified Linear Unit (ReLU)

>>>I. Visualizing ReLU

>>>II. Dying ReLU Problem

>>B. Leaky ReLU

>>>I. Visualizing Leaky ReLU

>>C. Sigmoid

>>D. Hyperbolic Tangent (Tanh)

>>>I. Visualizing Tanh

>>E. Softmax

>>>I. Visualizing Softmax

>6 - Challenges in Neural Network Training

>>A. Overfitting vs Underfitting

>>>I. Overfitting

>>>>a. L1/L2 Regularization

>>>>b. Dropout Layer

>>>>c. Early Stopping

>>>>d. Use More Data

>>>II. Underfitting

>>>>a. Add Network Complexity

>>B. Vanishing and Exploding Gradients

>>>I. Gradient Clipping

>>>II. Batch Normalization

>>>III. Weight Initialization

>>>IV. Use ReLU and Leaky ReLU

>>C. Computational Resources

>>D. Learning Rate Selection

>>>>I. Learning Rate Scheduler

>7 - Next Steps
</details>


## About

In this notebook, we will talk about the difference between Deep Learning and Machine Learning, we will talk about the architecture of a Feed-Forward Network (FFN), the algorithms to train one, and some of the challenges in Deep Learning training.

## Prerequisits

This notebook requires you understand:

1) How to write basic Python.
2) Basic Machine Learning (ML) Concepts:
     - Train vs Validation vs Test set
     - What is supervised learning?
     - What is the use-cases for ML?
3) Understanding basic Calculus and/or Linear Algebra is a plus.
