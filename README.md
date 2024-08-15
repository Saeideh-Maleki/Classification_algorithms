# Classification_algorithms
Project Title: Multilayer Perceptron (MLP) Classifier for Multi-Class Classification
Description:
This project implements a Multilayer Perceptron (MLP) classifier using scikit-learn to perform multi-class classification on a dataset containing four classes: 'Other', 'TRN', 'SOJ', and 'MIS'. This code is used for spatio-temporal transferability. For example to create map for Dijon 2020 using the training data of Tarbes 2021. The script evaluates the model's performance by computing various metrics, including accuracy, F1 score, precision, recall, Cohen's kappa, and the confusion matrix.

Script Overview:
Libraries Used:

numpy: For numerical operations.
sys and os: For system operations and handling input/output files.
scikit-learn: For the MLP classifier and evaluation metrics.
seaborn and matplotlib: For data visualization (confusion matrix).

Usage:
Input Data:

The script expects the training and testing datasets to be in .npz format.
The datasets should include specific arrays.
Output:

The script generates and saves performance metrics in a text file and the confusion matrix as a .png image.
The output is saved in the specified directory as txt file.
Customization:
Feature Selection:

You can customize the features used for training and testing by modifying the x_train and x_test variables in the script.
Model Parameters:

The MLP model's architecture can be modified by changing the hidden_layer_sizes parameter in the MLPClassifier.
Requirements:
Python
Required Python packages:
numpy
scikit-learn
matplotlib
seaborn
