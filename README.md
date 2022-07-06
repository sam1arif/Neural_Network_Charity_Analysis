# Overview of Analysis:

    In this analysis, we used deep-learning neural networks with TensorFlow in Python programming language to analyze and classify the results of a charity.

We used the following methods for the analysis for this project:

    a) preprocessing the data for the analysis/neural network
    b) compile, train and evaluate a model
    d) optimize the model
    
    
## Results:


 ### a) preprocessing:
  
          1. The EIN and NAME columns are removed.
          2. The column IS_SUCCESSFUL set as target for our neural network/deep learning analysis.
          3. The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT columns are set as features for the model.
          4. Categorical variables are encoded, split to training and testing datasets, and features have been standardized.
          
### b) compile, train and evaluate the model:
  
          1. we applied two layers for our model. Each layer had 80 and 30 neurons respectively.
          2. we used relu activation method for our input data and sigmoid method for output data.
          3. the accuracy of the model is 0.53. 
        
### c) optimize the model:
          1. we used adam optimizer and binary_crossentropy.
          2. even after three atempts, the model accuracy is under 75%. This is not accurate enough to predict the result of the charity donations.
          3. we also applied the tanh activation method to check if we could increase our efficiency but it did not help.
          
          
## Summary:
    
    The deep learning neural network model did not hit our desired result of 75% accuracy (even though it got close with our third attempt), meaning our model is not performing well enough for doing accurate predictions. 
Since the aim of the analysis is to find a yes/no answer (binary result), we would be better off if we used a supervised machine learning for this project instead of complicating it by using neural network or deep learning. 
          
          
  
    
   
