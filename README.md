# Predicting Customer Purchase with Neural Networks using AWS SageMaker

## Overview
This project demonstrates the creation of a simple neural network within an AWS SageMaker environment to predict customer purchases based on two features: website visit duration and number of pages visited. This is a binary classification problem commonly encountered in business contexts.

## Step-by-Step Instructions

### 1. Set Up AWS SageMaker Notebook
- Launch a new SageMaker notebook instance.
- Open a new Jupyter notebook in the instance.
- Choose kernel conda_tensorflow2_p310.

### 2. Generate Synthetic Data
Synthetic data is generated with two features: visit duration and pages visited. Labels indicating purchase or not are created based on a condition.

### 3. Preprocess the Data
The synthetic dataset is split into training and testing sets using the train_test_split function.

### 4. Build and Train the Neural Network
A simple neural network is constructed using TensorFlow's Sequential API. It comprises an input layer, hidden layers with activation functions, and an output layer. The model is compiled with suitable loss function and optimizer settings. Subsequently, it's trained on the training data.

### 5. Evaluate the Model
The trained model is evaluated on the test set to assess its accuracy in predicting customer purchases.

### Model Accuracy and Loss Visualization
Model accuracy and loss are essential metrics to evaluate the performance of the neural network. Visualizing the training process can provide insights into how the model learns over epochs. You can plot the training and validation loss and accuracy to understand the model's performance.

### Decision Boundary Visualization
The decision boundary is a critical concept in understanding how the neural network categorizes data. For our example with two input features, we can visualize the decision boundary on a 2D plot. This boundary separates the data points into different classes based on the model's predictions.

## Conclusion
This project showcases the utilization of AWS SageMaker for developing and training a basic neural network to address a common business problem. By predicting customer purchase behavior, businesses can gain valuable insights into customer preferences and improve decision-making processes.

