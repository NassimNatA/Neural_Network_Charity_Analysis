# Neural_Network_Charity_Analysis

## Overview

The purpose of this project is to utilize machine learning to evaluate features in the neural network dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by the company Alphabet Soup and to make informed decisions about potential investments. 

## Results: 
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?

The variable considered the target for this model is IS_SUCCESSFUL column.

- What variable(s) are considered to be the features for your model?

The variables considered to be features for this model are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, 
STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

- What variable(s) are neither targets nor features, and should be removed from the input data?

The variables that should be removed from the input data are EIN, NAME since they are not targets or features. 


### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

For my neural network model, I selected 2 layers with 80 nodes for the 1st layer and 30 nodes for the 2nd layer. This achieved an bal accuracy of 72.5%. 

![alt_text](https://github.com/NassimNatA/Neural_Network_Charity_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%202.09.08%20PM.png)

- Were you able to achieve the target model performance?

I was not able to get closer to target model performance after the three optimizations I applied. Each model had the same accuracy evaluation of 0.724781334400177 (72.5%). 

- What steps did you take to try and increase model performance?

The steps I took to try and increase the process model were to increase the nodes of the model, increase number of hidden layers, and decrease number of hidden layers shown below: 

![alt_text](https://github.com/NassimNatA/Neural_Network_Charity_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%202.18.39%20PM.png)
![alt_text](https://github.com/NassimNatA/Neural_Network_Charity_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%202.18.31%20PM.png)
![alt_text](https://github.com/NassimNatA/Neural_Network_Charity_Analysis/blob/main/Screen%20Shot%202021-01-10%20at%202.18.25%20PM.png)

## Summary

Despite numberous optimizations, our model stayed below the target 75% accuracy that was targeted. However, since this model is > 5% fromt the target accuracy, it can still provide valuable predictions for applicant success. A recommendation for how a different model could solve this classification problem is to further eliminate certain columns that are not targets of features in the dataset to furhter refine the input to this model. 
