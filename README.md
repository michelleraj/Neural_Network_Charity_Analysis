# Neural_Network_Charity_Analysis
## Overview of the Analysis
Utilised machine learning and neural networks, used features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
Alphabet Soup’s business team, CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Results


### Data Preprocessing
"IS_SUCCESSFUL " was considered as the target column
All the columns exxcept the target variable is considered as the input variable 
 Columns were dropped for dimensionality reduction EIN, Name
 
 ### Compiling, Training, and Evaluating the Model
 <img width="978" alt="Screen Shot 2021-11-23 at 8 24 04 PM" src="https://user-images.githubusercontent.com/57809798/143154128-87c810e7-c6d9-4967-a903-736637927e41.png">

 
 Activation layer, hidden layer and neurons used for the neural network
 #### First Attempt
-  Layer 1 : 80
-  Layer 2 : 30
-  hidden layer : 2
-  Accuracy of 72.9% 
  <img width="721" alt="Screen Shot 2021-11-23 at 10 03 19 PM" src="https://user-images.githubusercontent.com/57809798/143163937-63a3d8c2-83f5-4272-b982-4e697b4bb3cc.png">

  #### Second Attempt
-  Layer 1: 100
-  Layer 2: 70
-  Layer 3: 60
-  Hidden Layer: 3
-  Accuracy of 72.81%
  <img width="970" alt="Screen Shot 2021-11-23 at 9 28 44 PM" src="https://user-images.githubusercontent.com/57809798/143160528-a758f32e-7a27-4544-a0bf-59aeb2711b30.png">
<img width="735" alt="Screen Shot 2021-11-23 at 10 03 01 PM" src="https://user-images.githubusercontent.com/57809798/143163918-4fb251d8-fa7d-4887-9ae8-31e341e942d2.png">

  #### Third Attempt
-   Layer 1:  70 
-  Layer 2: 40
-  Layer 3: 30
-  Layer 4: 20
-  Hidden Layer: 3
-  Accuracy of 72.66%
<img width="944" alt="Screen Shot 2021-11-23 at 9 29 58 PM" src="https://user-images.githubusercontent.com/57809798/143160653-f100f733-d68e-4c2a-bdc2-0c9ef08a9dbc.png">

<img width="732" alt="Screen Shot 2021-11-23 at 9 59 16 PM" src="https://user-images.githubusercontent.com/57809798/143163584-edca30e9-68e1-4bd2-b89a-7b8fb2be9644.png">

  
  The Accuracy of all the neural networks came up to around 72%, and the loss was around 55 %. Lowering of the accuracy of the y test values after opitimization implies that the additional layers has resulted in overfitting of the curve
  


