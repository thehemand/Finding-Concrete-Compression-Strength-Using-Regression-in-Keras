Concrete Strength Prediction Using a Baseline Neural Network Model
This repository demonstrates a baseline neural network model for predicting concrete strength. 
The model is built using Keras and includes one hidden layer with ReLU activation. 
The process involves training the model on a dataset and evaluating its performance over 50 repetitions, 
each time generating a mean squared error (MSE) to assess prediction accuracy.

Project Overview
The main objectives of this project are:

Model Construction: Create a neural network model with one hidden layer of 10 nodes and ReLU activation.
Training and Evaluation: Train the model using the Adam optimizer and mean squared error (MSE) as the loss function.
Data Splitting: Randomly split the dataset into training and testing sets (70% training, 30% testing).
Model Performance: Train the model over 50 epochs and evaluate the performance on the test data using the mean squared error metric.
Repetition for Robustness: Repeat the entire process 50 times, storing the MSE values for analysis.


Steps
Data Splitting:
Randomly split the dataset into training (70%) and testing (30%) sets using train_test_split from Scikit-learn.
Model Training:

Build a neural network model in Keras with:
One hidden layer containing 10 nodes.
ReLU as the activation function.
Adam optimizer.
Mean squared error (MSE) as the loss function.
Train the model for 50 epochs.
Model Evaluation:

Evaluate the model's performance on the test data by computing the mean squared error (MSE) between predicted and actual concrete strength values using mean_squared_error from Scikit-learn.
Repetition:

Repeat steps 1 to 3 a total of 50 times.
Store the MSE results in a list for further analysis.
