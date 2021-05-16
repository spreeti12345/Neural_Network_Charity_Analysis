# Neural_Network_Charity_Analysis

Preprocessing Data for a Neural Network model and optimizing it

## Overview of the analysis:
Using my knowledge from machine learning and neural networks for this project I use the features in this dataset I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding amongst others. This project is comprised of 3 steps: Preprocessing the data for the neural network, Compile,train and evaluate the model & finally optimizing the model.

## Results:
Data Preprocessing
variable(s) that are considered the target(s) for your model?<br>
The variable we are targeting in this module is the IS_SUCCESSFUL column.<br>
variable(s) that are considered to be the features for your model<br>

The features that we are using are every column except the ones that we will drop.<br>
What variable(s) are neither targets nor features were removed<br>

First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model<br>

This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".<br>


Was the model able to achieve the target model performance?

Although we the target for the model was to be 75% or above, I was not able to reach the target.
What steps were taken to try and increase model performance?

Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.
adds

Summary:
The models accuracy ended up being 72.9% - we started with a data set and tried to predict whether or not the project would be successful on all of the features that we used after dropping two features that we figured to be irrelevant. Although I did not get to the accuracy of 75% that I wanted it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.
