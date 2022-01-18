# Neural_Network_Charity_Analysis
 Neural Networks and Deep Learning

 ### Module 19 Loan Prediction Risk Analysis
 **Deliverable 1, 2:** [AlphabetSoupCharity](AlphabetSoupCharity.ipynb) 
 **Deliverable 3:** [AlphabetSoupCharityOptimized](AlphabetSoupCharity_Optimization.ipynb) 
 
## Overview of the Loan Prediction Risk Analysis:
The purpose of this analysis is to train and test a deep learning neural network on our dataset to predict whether an organization will use the money effectively 

## Results:
- The target variable is the "IS_SUCCESSFUL" variable which decides contains either a 1 or 0 which tells us whether the money was used effectively (1: used effectively, 0: not used effectively).

- The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT columns before they are encoded are the features of the neural network

- The EIN and NAME were neither targets or features and were removed due to their lack of relevance to the model

- In the first layer there is 30 neurons with a relu activation function. The second layer had 16 neurons with a relu activation function. The output layer had 1 output with a sigmoid activation function.
The reason I used 30 neurons is that after going any higher I did not see better results and going lower was not any better, 16 neurons because its around half the first layer neurons and gave the best results.
The relu activation function gave the best results and the sigmoid for the output because its good for predictions.

- I was not able to achieve the target model performance but I was close with a accuracy of 72.52%

- The steps taken to increase the model performance: 
    - classification and apptype binning changed
    - number of nodes for both layers changed
    - standardized dataset(biggest boost in accuracy)

## Summary:
Overall the target model was not reached even after much tinkering with the deep learning neural network. A different model that could have been used is the Random Forest model because it is can handle many input variables, robust to outliers and nonlinear data and is effecient on large datasets.



 
