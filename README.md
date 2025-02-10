# Fully Connected Neural Network for Binary Classification in PyTorch

📝 Project Description

This project implements a fully connected two-layer neural network using PyTorch to classify a binary dataset. The network is trained to minimize classification error, and the progress of the loss reduction is visualized using a plot.

The dataset consists of (x1, x2) pairs with binary target labels. The neural network architecture is designed with two fully connected layers:\
	•	Hidden Layer: Contains 5 nodes. \
	•	Output Layer: Contains 1 node with a sigmoid activation function for binary classification.

The weights and biases of the network are initialized randomly between -2 and 2 as specified.

📂 Project Structure \
	•	neural_networks.ipynb: Contains the full implementation of the dataset preparation, neural network definition, training process, and error plotting. \
	•	README.md: Documentation explaining the purpose and steps in the project.

📊 Dataset

The input dataset consists of the following (x1, x2) pairs and their corresponding target labels:
| x1  | x2  | Target |
|-----|-----|--------|
| 1   | 1   | 0      |
| 1   | -1  | 0      |
| -1  | 1   | 0      |
| -1  | -1  | 0      |
| 5   | 5   | 1      |
| -5  | 5   | 1      |
| 5   | -5  | 1      |
| -5  | -5  | 1      |

🏗️ Neural Network Architecture: \
	•	Input Layer: 2 input features (x1, x2) \
	•	Hidden Layer: 5 nodes with sigmoid activation \
	•	Output Layer: 1 node with sigmoid activation for binary classification

Weight Initialization:
The weights and biases for both layers are initialized randomly between -2 and 2 to ensure diverse starting points for the optimization process.

🚀 Training Process \
	1.	Loss Function: Binary Cross-Entropy Loss (BCELoss) is used for binary classification. \
	2.	Optimizer: Stochastic Gradient Descent (SGD) with a learning rate of 0.1. \
	3.	Epochs: The model is trained for 1000 iterations.

 📈 Results \
	1.	Error Plot: The error is tracked at each iteration and visualized as a plot showing how the loss reduces during training. \
	2.	Final Weights and Outputs: The trained weights, biases, and output values are printed after training.
