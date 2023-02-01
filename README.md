# Neural_Network_Charity_Analysis


# Overview 

The purpose of this analysis was to create a ML model that is able to accurately predict if a business will be successful if it is backed by the company Alphabet. I worked with a dataset of more than 33,000 organizations and many different features including the use case for the company, organization type, the current income info, and the funding amount asked. 

# Results 

### Data Preprocessing 

  - The target variables from the dataset was 'IS_SUCCESSFUL' and was separated from the remained of the dataset. 
  - The variable features I considered are listed below. 
      - APPLICATION_TYPE 
      - AFFILIATION               
      - CLASSIFICATION            
      - USE_CASE                 
      - ORGANIZATION              
      - STATUS                    
      - INCOME_AMT                
      - SPECIAL_CONSIDERATIONS    
      - ASK_AMT
      
    - The variables that were taken out and not considered were EIN number and the name of the company. 
    Other things to considered for preprocessing is consolidating the different values of the columns by binning. Also using encoding to transform all values into numerical values. 
    
  - Compiling. training, evaluating 
  
    - For the first model test I used two hidden layers, layer one containing 80 neurons and layer two containing thirty. The activation functions used was relu for the first two layers and sigmoid for the output layer. Using 100 epochs this was the result. 
    ![This is an image](https://github.com/BrandonCodes95/Neural_Network_Charity_Analysis/blob/43a31b46a6d920a9521e80398c72f74d889333f1/ML%20Model%201%20loss.PNG) 
    
     -The best model had three hidden layers. The first with one-hundred and fifty neurons, the second with eighty neurons, and the third with forty neurons. The activations were sigmoid, relu, and tanh with an output activation of sigmoid. 
    To try and increase performance I increased the binning making the grouping tighter and less categories. Also increased the number of hidden layers and neurons. The image below shows the results. 

    ![This is an image](https://github.com/BrandonCodes95/Neural_Network_Charity_Analysis/blob/43a31b46a6d920a9521e80398c72f74d889333f1/ML%20Model%202%20accuracy.PNG) 
    
    
