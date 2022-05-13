# Deep Learning HW - Alphabet Soup

Report

**Overview**

The purpose of this analysis was to create an algorithm for Alphabet Soup to predict whether funding for applicants will be successful by using binary classifiers. 


**Results**

- Data Preprocessing
  - What variable(s) are considered the target(s) for your model?
    - IS_SUCCESSFUL (0- NOT SUCCESSFUL, 1- SUCCESSFUL)
  - What variable(s) are considered to be the features for your model?
    - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPEACIAL_CONSIDERATIONS, ASK_AMT
  - What variable(s) are neither targets nor features, and should be removed from the input data?
    - EIN was dropped from the dataset because it provides no useful identifier 
    - STATUS was removed in the optimization portion because there were comparibly minimal 0s in the dataset
    - SPECIAL_CONSIDERATIONS was removed in the optimization portion because there were comparibly minimal Ys in the dataset
- Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Selected 3 layers, of 100, 30, 10 nodes, activations relu & sigmoid each to optimize the model further than the initial model 
  - Were you able to achieve the target model performance?
    - Yes, Accuracy of 79.6%
  - What steps did you take to try and increase model performance?
    - increasing the number of layers and the activation types within the neural network model 

**Summary**

By increasing the number of layers, neurons, and altering activation functions, the neural network was improved in accuracy compared to the first model. 
An alternate model to use could be the random forest classifer to comparibly classify the data. 
