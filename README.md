# Neural_Network_Charity_Analysis

## Overview

#### The goal of this analysis is to use a neural network to determine which companies should be financed by Alphabet Soup. This analysis uses Python's TensorFlow library to build, train, and evaluate data collected from previous borrowings. With some knowledge of machine learning and neural networks, Beks created a binary classifier that could use features from the provided dataset to predict whether an applicant would be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing:
#### What variable(s) are considered the target(s) for your model?
#### The target is held in IS_SUCCESSFUL field.

#### What variable(s) are considered to be the features for your model?
#### APPLICATION_TYPE	AFFILIATION	CLASSIFICATION	USE_CASE	ORGANIZATION	STATUS	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AMT	

#### What variable(s) are neither targets nor features, and should be removed from the input data?
#### NAME & EIN

### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
#### hidden_nodes_layer1 = 8, hidden_nodes_layer2 = 5


#### Were you able to achieve the target model performance?
#### On my ifrst model I was not able. Accuracy: 0.7337609529495239
