# deep-learning-challenge
module 21

# Overview
Create a model for Alphabet Soup that can help select applicant for funding with the best chance of success.

# Data Preprocessing
Target variable:
- IS_SUCCESSFUL

Feature variables:
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT


Varibales removed:
- EID
- NAME
- STATUS
- SPECIAL_CONSIDERATIONS

# Compiling, Training, and Evaluating the Model
## Model
I used the below model because I figured the first layer could learn more about the lower level features and that would feed the next layer which had fewer neurons, hopefully helping with the loss.
- Number of neurons: 40 for the 1st layer and 20 for the 2nd layer
- Number of layers: 3
- Activation functions: 'relu' for 1st and 2nd layer, 'sigmoid' for outer layer

## Performance
I did not achieve the 75% accuracy threshold for the model created. Instead, I was able to create a model with 72.43% accuracy and 55% loss.
I tried several different models, adjusting the number of layers and neurons, but was unable to create a model with higher accuracy.

# Summary
The final model created has 72% accuracy, used 2 hidden layers with the first having 40 neurons and the second having 20. If there were more context on the data, then it may have been possible to remove some additional features in the dataset.

