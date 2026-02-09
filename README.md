
# MNIST_Optimization_Algorithms_Performance_Comparison

## Overview

This project compares the performance of various optimization algorithms in training a shallow neural network on the MNIST dataset. The goal is to evaluate how different optimization techniques impact training time and classification accuracy.

### Optimization Algorithms Implemented:
- **Stochastic Gradient Descent (SGD)**
- **Gradient Descent with Momentum**
- **Gradient Descent with Adaptive Learning Rate**
- **Adagrad**
- **Adam**

Each algorithm is evaluated in terms of:
- **Training Time**: How long each optimization algorithm takes to converge.
- **Accuracy**: The classification accuracy achieved on the MNIST dataset.

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## Installation

Clone the repository and install the dependencies using:

```bash
git clone https://github.com/Omar-Elshawaf/MNIST_Optimization_Algorithms_Performance_Comparison.git
```

```bash
cd MNIST_Optimization_Algorithms_Performance_Comparison
```

```bash

pip install tensorflow
pip install numpy
pip install matplotlib

```

## How to Run
**- Running on Google Colab**
1- Open a new notebook on Google Colab
2- Clone the repository into your Colab environment:
```bash
git clone https://github.com/username/MNIST_Optimization_Algorithms_Performance_Comparison.git
```
Navigate into the cloned directory:

```bash
cd MNIST_Optimization_Algorithms_Performance_Comparison
```
3- Run the cells one by one to execute the optimization algorithms on the MNIST dataset.

**- Running on Jupter Notebook**

Make the same and run the cells one by one to execute the optimization algorithms on the MNIST dataset.


Run the main script to train the model using different optimization algorithms:


This will execute the code in the notebook, which:
1. Loads the MNIST dataset.
2. Defines a shallow neural network model.
3. Trains the model using each of the five optimization algorithms.
4. Records the training time and accuracy for each algorithm.



## Experimental Results

The project provides a detailed comparison of training time and accuracy for each optimization algorithm. Visualizations such as loss vs. iterations and accuracy vs. iterations will help analyze the efficiency and effectiveness of each method.



## Output & Results Visualization:


Graphs showing loss and accuracy over iterations for each optimization algorithm are included in the results folder. These graphs help visualize the convergence behavior of each optimizer.

<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/01a68b59-49ee-4dc8-8709-a05bd12f6594" />
<img width="855" height="547" alt="image" src="https://github.com/user-attachments/assets/8f30aa90-50af-4e85-be14-73c8fc4787a2" />
<img width="846" height="579" alt="image" src="https://github.com/user-attachments/assets/1e0731dc-a017-4ccc-a6d1-a325753fb8ba" />
<img width="855" height="528" alt="image" src="https://github.com/user-attachments/assets/9a425522-dd09-4426-a4f9-92ac6630b427" />
<img width="863" height="528" alt="image" src="https://github.com/user-attachments/assets/7664e659-2697-459f-af5b-a1c178de6937" />
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/aa885b9d-f2bc-4ad3-bb3e-17b2b40a0b8c" />
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/15ebb91e-4aee-4947-8f04-86c7ac54601e" />
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/75c888d8-d322-436c-9abc-c88db2b84a2b" />
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/353e1924-1e1a-4b2f-abdb-0cca0c438d85" />
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/18d579b8-07c2-4e13-9149-d0099bfbae0d" />







