
# Machine Learning & Neural Networks

A collection of hands-on Machine Learning, Deep Learning, and Reinforcement Learning experiments developed using Python.

This repository explores different neural network architectures and learning algorithms through implementation, experimentation, and performance evaluation.

## Projects

### 01. MLP vs CNN — Fashion-MNIST

Comparison of Multilayer Perceptron (MLP) and Convolutional Neural Network (CNN) architectures for clothing image classification.

**Key Findings**
- MLP Test Accuracy: 88.30%
- CNN Test Accuracy: 90.84%
- CNN achieved higher accuracy, while MLP trained faster.

[View Project](./01-MLP-vs-CNN-FashionMNIST/)

### 02. MLP vs RNN — MNIST

Comparison of MLP and Recurrent Neural Network (RNN) architectures for handwritten digit classification.

Experiments were performed using five random seeds to evaluate average performance and consistency.

**Key Findings**
- MLP Test Accuracy: 97.49%
- RNN Test Accuracy: 97.16%
- RNN used approximately 80% fewer trainable parameters.
- MLP achieved slightly better accuracy and faster training.

[View Project](./02-MLP-vs-RNN-MNIST/)

### 03. Q-Learning vs SARSA — Cliff Walking

Comparison of two reinforcement learning algorithms in the Cliff Walking environment.

The experiment investigates off-policy and on-policy learning, agent decision-making, exploration, and risk.

**Evaluation**
- Average reward
- Steps per episode
- Cliff falls
- Learned policies
- Performance across multiple random seeds

[View Project](./03-Q-Learning-vs-SARSA-CliffWalking/)

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure

Machine-Learning-Neural-Networks/
- README.md
- .gitignore
- requirements.txt
- 01-MLP-vs-CNN-FashionMNIST/
- 02-MLP-vs-RNN-MNIST/
- 03-Q-Learning-vs-SARSA-CliffWalking/

## Purpose

The purpose of this repository is to strengthen practical machine learning skills through model implementation, comparative experiments, and analysis of experimental results.

Future projects will explore additional machine learning and reinforcement learning techniques.
