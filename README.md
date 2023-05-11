# Classifying Zoo data using Neural Networks

This repository contains code and resources for classifying animals in the Zoo dataset using neural networks with multiple hidden layers. The aim is to build a model that accurately predicts the type of an animal based on its attributes. In this project, we explore two different neural network architectures: one with 4 hidden layers and another with 8 hidden layers. The goal is to compare their performance and understand how increasing the number of hidden layers affects the model's learning and generalization abilities.

### Dataset
The Zoo dataset is a popular machine learning dataset consisting of 101 animal instances. Each animal is described by 16 attributes, including features like hair, feathers, eggs, milk, airborne, aquatic, predator, and more. The target variable is the animal type, with values ranging from 1 to 7, representing different classes such as mammals, birds, and reptiles.


### 4 Hidden Layers
The neural network architecture with 4 hidden layers consists of an input layer, 4 hidden layers, and an output layer. Each hidden layer contains a different number of neurons, enabling the model to capture various levels of complexity in the data. By adding more hidden layers, the model can potentially learn more intricate patterns and representations.

### 8 Hidden Layers
The neural network architecture with 8 hidden layers is similar to the one with 4 hidden layers, but it has a greater number of hidden layers. This increased depth allows the model to capture even more complex relationships in the data. However, as the number of layers increases, it might lead to the problem of diminishing returns or overfitting.

### Diminishing Returns and Overfitting
When comparing the performance of the models with 4 and 8 hidden layers, we need to consider the balance between model complexity and generalization ability. Adding more hidden layers can improve the model's ability to fit the training data more precisely, potentially reducing the training error. However, this increased complexity may lead to overfitting, where the model becomes too specialized to the training data and performs poorly on unseen data.

In the implemented model, the attempt at accuracy improvement from 4 hidden layers to 8 hidden layers demonstrates diminishing returns. While the deeper network improved performance, the gain in accuracy was not as substantial as between the initial model and the one with 4 hidden layers. Additionally, the risk of overfitting increases with more hidden layers, making it important to monitor the model's performance on unseen data.

