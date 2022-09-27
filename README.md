# Neural_Network_Charity_Analysis
We wanted to use a deep learning neural network to analyze and classify charitable donations from the data provided by Alphabet Soup.
# Results

## Data
We considered the "IS_Successful" variable to determine if the donattion was used effectively. We can also consider other variables to be the features of the model, these are: 
-APPLICATION_TYPE
-AFFILIATION
-CLASSIFICATION
-USE_CASE
-ORGANIZATION
-STATUS
-INCOME_AMT
-SPECIAL_CONSIDERATIONS
-ASK_AMT

![This is an image](https://github.com/rafaq2000/Neural_Network_Charity_Analysis/blob/main/Images/application_df.png)

## Compiling, Training, and Evaluating the Model
At first, for the model, we used 2 layers with 80 and 30 neurons respectively. As for activation fuctions we did "relu" and "sigmoid". We wanted to see if this was the most effcient way of reaching 75% accuracy. However this was not the case, the output we got was of 63%.

![This is an image](https://github.com/rafaq2000/Neural_Network_Charity_Analysis/blob/main/Images/First%20Model.png)

![This is an image](https://github.com/rafaq2000/Neural_Network_Charity_Analysis/blob/main/Images/First%20Model%20Results.png)

It was decided that an optimization was required to see if the desired 75% accuracy could be reached, for this we instead used 5 hidded layers of 200, 180, 150, 110, and 90 neurons respectively with "tanh" and "sigmoid" activation functions, this increased accuracy to 72%.

![This is an image](https://github.com/rafaq2000/Neural_Network_Charity_Analysis/blob/main/Images/Optimization%20%20Model.png)

![This is an image](https://github.com/rafaq2000/Neural_Network_Charity_Analysis/blob/main/Images/Optimization%20%20Model%20Results.png)

## Summary
The current deep learning model has an accuracy of 72% and a loss of 57%. Three optimization trials were run to try to achieve the target 75% accuracy. More layers and neurons were added in each try, as well as different activation functions. However, the target was not reached, perhaps a different activation function must be used to optimize the current model. 
