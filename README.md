# Neural Network Implementation - CS3630 Assignment 1

This repository contains the implementation of a neural network for CS3630 Assignment 1. The goal of this assignment was to implement a neural network, perform backpropagation, and train the network using gradient descent.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Discussion](#discussion)
- [Appendix](#appendix)
- [License](#license)

## Overview

In this assignment, I implemented a neural network to classify data points into four classes. The network architecture consisted of an input layer, a hidden layer with ReLU activation, another hidden layer with ReLU activation, and an output layer with a softmax activation function. I used Python 3.6 and standard libraries such as NumPy for the implementation.

## Project Structure

The project is structured as follows:

- `code/`: This directory contains the Python code for the neural network implementation, backpropagation, and training.

- `Task_1/`: This directory contains the results for Task 1, including the gradients for 𝑊1 and 𝑏1 in CSV format.

- `Task_2/`: This directory contains the data and code for Task 2, where we trained the neural network with different learning rates and generated plots for training cost, testing cost, and accuracy scores.

## Usage

To run the code, follow these steps:

1. Clone this repository to your local machine.

2. Navigate to the `code/` directory.

3. Run the Jupyter Notebooks

## Results

The results of the assignment are stored in the `Answer/` directory. Task 1 includes the gradients for 𝑊1 and 𝑏1, while Task 2 contains the plots for training and testing costs, as well as accuracy scores for different learning rates.

## Discussion

In the two-page report (not included in this repository), I discussed the influence of learning rate on test accuracy and presented the graphs from Task 2.

## Appendix

- `sample_evaluation_script.py`: This script can be used to verify the format of the submission for grading.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
