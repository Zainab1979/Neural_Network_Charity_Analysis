# Neural_Network_Charity_Analysis
## Overview of the analysis
In this project we aim to apredict if an application will be successful if funded by  Alphabet Soup. 
We use adataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.
Each row contains information about organization and if the application was succsseful.
To achive this we trained nueral network model using  TensorFlow library.
## Results
- Data Preprocessing
We used S successful as target variable, We removed EIN and NAME variable from the dataset and we use all other variable as features. <br>
- Compiling, Training, and Evaluating the Model 
We desied nural network with four hidden layers that have 300,200,100 and 50 in each layer.
We used Relu activation function for all hidden layers and train the model for 200 epochs.
To improve the model performance we increase the number of hidden layers, unties and epochs.
- Summary:
Our first model achieved test accuracy of 0.736 as show in the screenshot.
![Over_sampling]() <br> 
