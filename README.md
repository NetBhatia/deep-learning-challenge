Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

Instructions
Step 1: Preprocess the Data
Step 2: Compile, Train, and Evaluate the Model
Step 3: Optimize the Model

Analysis Report:

Overview of the analysis: 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. 

For this purpose data contained in the csv file is reviewed and pre-processed to create a model to predict the applicants' performance.

Results: 
Data Preprocessing

The column "Is_Successful" is considered as variable(s) and is the target(s) for the model. Remaining columns are the features for your model?
EIN and Name (identification columns) were removed from the input data because they were neither targets nor features.

Compiling, Training, and Evaluating the Model

Model was created initially with 2 layers and then 3 layers. However, the performance could not exceed 74% despite 3 attempts.

To increase model performance, count of epochs were changed, activation functions were changed (relu/tanh), number of hidden layers were increased. However, it still did not improve.

Summary: The model's performance remained around 74% that means model's prediction would align 74% times with actual results.
