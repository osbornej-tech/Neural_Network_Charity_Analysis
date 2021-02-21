# Neural_Network_Charity_Analysis
# Overview of the Analysis
In this project, we utilized a dataset that contains information from a loan funding application. We selected features from the dataset to create a binary classifier that predicts money invested into a organization will be used effectively.

The dataset columns and their description are as follow:

|Column Name|Description|
| --- | --- |
|EIN and Name|Identification Columns|
|APPLICATION_TYPE|Application type|
|AFFLICATION|Affliliaated sector of industry|
|CLASSIFICATION|Government organziation classification|
|USE_CASE|Use case for funding|
|ORGANIZATION|Organization type|
|STATUS|Active Status|
|INCOME_AMT|Income Classification|
|SPECIAL_CONSIDERATION|Special consideration for application|
|ASK_AMT|Funding amount requested|
|IS_SUCCESSFUL|Was the money used effectively|

The processes used in this project include: preprocessing of the data for a neural network model, compile, train and evalaute the accuracy of the models and optimization of the model. 

# Results
## Data Preprocessing
* What variable(s) are considered the target(s) for your model? Target variable is the is_sucessful column as we are trying to predict the likelihood of an organization to effectively using the funding recieved.
* What variable(s) are considered to be the features for your model? Variables used in the model include: application type, affiliation, classification, use case, organization, status, income amount, special consideration, and ask amount. 
* What variable(s) are neither targets nor features, and should be removed from the input data? EIN is neither a target or feature variable

## Compiling, Training and Evaluating the Model
Relu activation provides user information about the nonlinear relationship. We utilize the sigmoid acitcation function to produce probability outputs. 

* How many neurons, layers, and activation functions did you select for your neural network model, and why? In the optimization level, the following neurons 100, 75, 20 were selected for layers one to three, respectively. The Relu activation function was used on all hidden layers; while, sigmoid activation was used for the output layer. The about mentioned selections were selected to increase the accuracy of the model and to prevnt overfitting.
* Were you able to achieve the target model performance? With the model, we were able to acchieve the target result with -- % accuracrt.
* What steps did you take to try and increase model performance? To increase the model performance, I changed the number of neurons, dropped a few columns that were relevant to the model, adjust the hidden layers and changed the number of binnings.


# Summary
Summary of the Results: 
To improve the accuracy of the model, we group values into bins, increase the number of hidden layers, activation function for the hideden layers .
In the optimized version, the following variables were excluded: EIN, Is_successful and the Ask_Amt fields.

Recommendation
