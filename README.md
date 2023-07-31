# Digit-Recognition
This repository contains a Digit Recognizer project using PyTorch. The goal is to build a neural network model that can accurately recognize handwritten digits from 0 to 9.

##Methodology
- Importing Required Libraries: The project imports necessary libraries for deep learning and visualization.

- Extract Data from MNIST Dataset: Data is extracted from the MNIST dataset containing images of handwritten digits.

- Separate Features and Labels: Features (images) and labels (digit labels) are separated to prepare the data for training and testing.

- Split Data into Training and Testing Sets: The dataset is split into training (60,000) and testing (10,000) examples for training and evaluation.

- Shuffling the Data: The data is shuffled to enhance training performance and prevent bias.

- Initialize the Optimizer: The optimizer is initialized to train the neural network and update weights during backpropagation.

- Train the Model: The neural network model is trained using the chosen optimizer and loss function to minimize errors.

- Calculate Accuracy and Precision: The model's performance is evaluated on the test set, and accuracy and precision are calculated for evaluation.

##Requirements
To run the code, you need Python 3.x with the following dependencies:

- PyTorch
- torchvision
- matplotlib
- tqdm
