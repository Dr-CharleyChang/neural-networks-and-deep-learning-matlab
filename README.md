# 🧠 Neural Networks & Deep Learning (MATLAB Core)

![Language](https://img.shields.io/badge/Language-MATLAB-orange.svg) ![License](https://img.shields.io/badge/License-MIT-blue.svg) ![Platform](https://img.shields.io/badge/Platform-Ubuntu_|_Windows-lightgrey.svg)

> **Note:** This repository demonstrates the mathematical foundations of Deep Learning. It implements **Stochastic Gradient Descent (SGD)** and **Backpropagation** algorithms from scratch using pure MATLAB matrix operations, without relying on high-level frameworks like PyTorch or TensorFlow.

## 📖 Overview
This project is a vectorized MATLAB implementation based on the classic book **[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)** by Michael Nielsen.

The goal is to provide a transparent, "white-box" understanding of how a neural network learns to recognize handwritten digits (MNIST) purely through linear algebra and calculus.

## ✨ Key Features
* **Zero Dependencies**: No Deep Learning Toolboxes required.
* **Vectorized Implementation**: Optimized matrix multiplications for faster training speed.
* **Core Algorithms**:
  * Feedforward propagation
  * Backpropagation (The engine of learning)
  * Stochastic Gradient Descent (SGD)

## 🚀 Quick Start

### 1. Prerequisites
* **MATLAB R2022b** or later (Verified on Ubuntu 64-bit & Windows).

### 2. Dataset Setup (Critical Step)
To keep the repository lightweight, the dataset is not included.
1. **Download** `mnist.mat` from this mirror: [lucidar.me/mnist.mat](https://lucidar.me/en/matlab/files/mnist.mat)
2. **Place** the `mnist.mat` file in the root directory of this project.

### 3. Run Training
Open MATLAB and execute the main script:
```matlab
>> main
