# diabetes
 Diabetes Prediction Model Using Keras
This project demonstrates how to create a neural network model using Keras to predict diabetes based on input data.

Files
diabetes.csv: Dataset containing features and labels for training.
model.json: JSON file to save the model architecture.
weights.h5: File to save the trained model weights.
Code Overview
Import Libraries:

loadtxt from NumPy to read CSV data.
Keras modules for model creation, training, and saving.
Load Dataset:

The dataset is loaded with loadtxt and split into input (x) and output (y) features.
Define the Model:

A sequential model with three layers:
Input layer with 12 neurons.
Hidden layer with 8 neurons.
Output layer with 1 neuron using the sigmoid activation function.
Compile and Train the Model:

The model uses the adam optimizer and binary cross-entropy loss.
Trained for 90 epochs with a batch size of 10.
Evaluate and Save the Model:

Accuracy is calculated on the same dataset.
Model architecture and weights are saved separately as model.json and weights.h5.
Usage
Ensure diabetes.csv is present in the same directory.
Run the script to train the model.
Access the saved model files (model.json and weights.h5) for reuse.
Requirements
Python 3.x
NumPy
TensorFlow/Keras
