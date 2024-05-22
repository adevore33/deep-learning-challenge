# deep-learning-challenge

Overview:
The purpose of this project was to understand the effects that model hyperparameters have on the model fit.

Data Preprocessing:
The variable in focus for this model is the column "IS_SUCCESSFUL" which shows whether the money from the funding was used effectively.
The Features of the model were alphabet soup application type, affiliated sector of industry, government organization classification, organization type, active status, income classification, and ask amount.
EIN and NAME column were removed since they were not targets.  Along with Special considerations and use case for better attempts.

The Model:
I used 4 layers with less neurons each layer in order to help with the accuracy of the model.
I did not get to 75% target performance.
I tried changing target fields by removing columns, but this made the accuracy worse.  Adding neurons, layers and epochs did seem to add to the accuracy.

The model was able to predict a success of funding having a 73% accuracy.  One way to increase the accuracy is use random forest feature tool to limit the data to just the features that are above certain importance.