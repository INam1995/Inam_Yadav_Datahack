# Inam_Yadav_Datahack
This repository is for the submission for the Hackathon by GeeksForGeeks under the Summer Analytics course from IIT-G '24.


## Problem description
Our goal is to predict how likely individuals are to receive their xyz and seasonal flu vaccines. Specifically, we'll be predicting two probabilities: one for xyz_vaccine and one for seasonal_vaccine.


### Checking purpose
- Code: `Data_Hackathon.ipynb`
- Output CSV: `predictedAnswer.csv`

## Overview
To predict probabilities, I have used Randomforest Classifier Model and Performance have evaluated according to the area under the receiver operating
characteristic curve (ROC AUC) for each of the two target variables. 
ROC AUC scores have been calculated on the validation set and are being displayed in the output which can be seen in the Data_Hackathon.ipynb file.
#### The final result has been stored in the "predictedAnswer.csv".
#### In this Project , Achieved Mean ROC AUC Score: 0.8550.


## Steps formed in building this model to Calculate the probabilities :
#### 1. Loading the Dataset
#### 2. Preprocessing and cleaning of Training Data
###### i) One hot encoding
###### ii) Data Normalization
#### 3. Building the Random Forest Classifier Model
###### i) Train the model
###### ii) Predict Probabilities for testing data
###### iii) Calculation of ROC AUC Scores 
#### 4. Saving predictions into final dataframe


### Proper comments in the code is given for better readability and understanding the idea behind the solution.


## Technologies Used
- Programming Languages: Python
- Libraries: Pandas, Numpy, Sk-Learn, AUC



## Dataset used for training the model:
#### 1. test_set_features.csv
#### 2. training_set_labels.csv
#### 3. training_set_features.csv

## More information about Project and Dataset :
- `Problem description.pdf`

