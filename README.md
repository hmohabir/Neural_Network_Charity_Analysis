# Neural_Network_Charity_Analysis
Module 20

## Overview

An analysis was preformed using Machine Learning and Neural Network. A featured dataset was used to predict weather applicants will be successful if funded by the charitable organization, Alphabet Soup. This project is comprized of the following:

- Preprocessing the data for the neural network 
- Compile, Train and Evaluate the Model 
- Optimizing the model

## Results

### Data Preprocessing

Columns that did not contain non-leanear data and uneccessary data were dropped. 

![Raw Data](https://github.com/hmohabir/Neural_Network_Charity_Analysis/blob/main/Raw%20data.PNG)

These include the EIN and NAME columns from the dataset. Encoded variable names were also added. 

![Cleaned Data](https://github.com/hmohabir/Neural_Network_Charity_Analysis/blob/main/one-hot%20encoded.PNG)

- Variable that was examined as the target for my model was: IS_SUCCESSFUL Column
- Variables that were examined as  features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
- Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they had little or no impact on the outcome.

### Compiling, Training and Evaluating the Model

- I used two hidden layers fo rmy neural network. For my first layer, I used  80 neurons and 30 neurons in my second layer. I also had an output layer. I also used the 'RELU' activation function with a sigmoid function for the outer layer.

![Deep Neural](https://github.com/hmohabir/Neural_Network_Charity_Analysis/blob/main/Deep%20Neural.PNG)

- My attempt to obtain a more accrurate depiction of over 75% was not successful.

My first accruracy was 40%

![First Deep Neural](https://github.com/hmohabir/Neural_Network_Charity_Analysis/blob/main/First%20accruracy.PNG)

In trying to make my prediction more accrurate, I got 54%.

![Second Deep Neural](https://github.com/hmohabir/Neural_Network_Charity_Analysis/blob/main/Second%20accruracy.PNG)

- To increase my model's performance, I added a third hidden layers and added 100, 50 and 20 neurons respectively. I also used the RELU activation.

## Summary

The data was first preproccessed and trained. It was then optimized further in order to achieve more accruracy. The model ended up with 54% accruracy after optimization. The model might have been overfitted. 
As a recommendation, Random Forest Classifier could have been used as another model. This might have presented more accruracy as it is robust and more accrurate. Also data overfitting could have been avoided with this model.

