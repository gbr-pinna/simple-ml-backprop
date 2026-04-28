# simple-ml-backprop

A from-scratch implementation of backpropagation in Python, demonstrating how gradients are computed and propagated through a computational graph. The project applies this core mechanism to train a simple multilayer perceptron (MLP) using gradient descent, without relying on any deep learning frameworks.

---

## Overview

This project focuses on the core idea behind neural network training: **backpropagation**.

Instead of using libraries like PyTorch or TensorFlow, everything is implemented manually in Python, including:

- A minimal automatic differentiation system  
- Forward and backward passes through a computational graph  
- Topological sort to process nodes in the correct order during backpropagation  
- Gradient computation using the chain rule  
- Parameter updates via gradient descent  

The backpropagation engine is then used to train a simple MLP on toy datasets.

---

## Features

- Pure Python implementation (no ML frameworks)
- Manual computation graph / autograd system
- Backpropagation via the chain rule
- Training with gradient descent
- Experiments on synthetic datasets
