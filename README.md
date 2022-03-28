# Neural_Network_Charity_Analysis

![](https://github.com/lightbright832/Neural_Network_Charity_Analysis/blob/main/neural%20networks.png)

## Overview of the analysis
### Purpose:

When decided to fund a project it is important to know whether the project will be successful. Throughout this analysis machine learning tools and neural network models it is possible to made determinations prior to funding. The models will help with predictions that will be used throughout the decision making process. 

## Results

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
The variabe that is considered the target of the model is the "Is Successful" variable. This will help to determine if the chartiy is worthy of funding.
* What variable(s) are considered to be the features for your model?
The variables that are considered to be the features for the model are, "binary_crossentrophy", "adam", and "accuracy".
* What variable(s) are neither targets nor features, and should be removed from the input data?
The variables to drop are "EIN" and "Name".

### Compiling, Training, and Evaluating the Model

![](https://github.com/lightbright832/Neural_Network_Charity_Analysis/blob/main/images/attempt%201.png)

![](https://github.com/lightbright832/Neural_Network_Charity_Analysis/blob/main/images/attempt%202.png)

![](https://github.com/lightbright832/Neural_Network_Charity_Analysis/blob/main/images/attempt%203.png)


* How many neurons, layers, and activation functions did you select for your neural network model, and why?
The initial number of neurons, layers, and activation functions were 86,30, and 13. Additional layers were added with attempt 2 and 3. 
* Were you able to achieve the target model performance?
I was not able to achieve the target model performance of 75% accuracy.
* What steps did you take to try and increase model performance?
To increase model performance I increased the number of neurons and layers with each attempt. With each additional attempt the accuracy rating went down.

![](https://github.com/lightbright832/Neural_Network_Charity_Analysis/blob/main/images/neural%20networks%202.jpg)

## Summary: 
The results of the analysis show that deep learning can be instrumental in helping with the decision making process. Based on the results provided by this analysis the more layers there are the further away from ideal performance you are. The goal is to get to 75% accuracy so I would try to go down in the number of neurons, layers, and activation functions instead of going in the other direction.
