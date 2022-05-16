# Neural_Network_Charity_Analysis
Using neural networks to determine of applicants will be successful if funded by Alphabet Soup.

## Overview of the Analysis
The purpose of the analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup using a neural network.

## Results

### Data Processing

#### Target Variable
![image_name]()

The target variable for the model is the "IS_SUCCESSFUL" column. It is a column that indicates if an organization was successful at obtaining funding.

#### Feature Variable
![image_name]()

There are 10 feature variables in the final model. They are:
- NAME
- APPLICATION TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- ASK_AMT

#### Dropped Variable
![image_name]()

The variable that was dropped in the final model was the "EIN" column. This column was just a unique identifier and would not be useful for discovering trends and patterns.

### Compiling, Training, and Evaluating the Model

#### Neurons, Layers, and Activation Functions

![image_name]()

The final model has three hidden layers. Below is a description of each layer:

First Layer: 90 neurons and uses the relu activation function.
Second Layer: 38 neurons and uses the relu activation.
Third Layer: 20 neurons and uses the tanh activation.

With each addition of a layer and neuron, the model becomes more accurate.

#### Target Model Performance
After adding additional layers, neurons, and changing the activation function for certain layers, the model surpassed the target and reach 78% accuracy.

#### Steps taken to Improve Model Performance
The steps that were taken to improve the models performance were:
- Adding additional neurons
- Changing the activation function from relu to tanh in layer 3
- Including the 'NAME' column as a feature variable
- Increasing the epochs from 100 to 200

## Summary

The model is relatively strong when it comes to predicting if an organization will be successfully funded by Alphabet Soup (approximately 78% accuracy). Another model that could solve this classification problem is Random Forest. Random forest classifiers would combine multiple smaller models into a more robust and accurate model. Random forest models use a number of weak learner algorithms (decision trees) and would combine their output to make a final classification.

