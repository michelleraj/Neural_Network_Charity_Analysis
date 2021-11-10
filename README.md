# Neural_Network_Charity_Analysis
## Overview of the Analysis
Utilised machine learning and neural networks, used features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
Alphabet Soup’s business team, CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Results

### Data Preprocessing
"IS_SUCCESSFUL " was considered as the target column
All the columns exxcept the target variable is considered as the input variable 
 Columns were dropped for dimensionality reduction EIN, Name
 
 ### Compiling, Training, and Evaluating the Model
 
 Activation layer, hidden layer and neurons used for the neural network
 #### First Attempt
 Layer 1 : 80
  Layer 2 : 30
  hidden layer : 2
  Accuracy of 72% 
  
  #### Second Attempt
  Layer 1: 100
  Layer 2: 50
  Layer 3: 20
  Hidden Layer: 3
  Accuracy of 68%
  
  Lowering of the accuracy of the y test values after opitimization implies that the additional layers has resulted in overfitting of the curve
  


