# Realistic Ocean Climate - Machine Learning
## Marine Heatwave Analysis Project

## Project Overview

This project analyzes marine heatwave data to understand the factors contributing to marine heatwaves and to build machine learning models that predict their occurrence.
*************
## Data
- The original dataset is stored in the Data folder as original_dataset.csv.
- The dataset is split into training and testing sets, saved in the Data/train_test_split folder.
- The predicted results from various models are saved in the Data/Result folder.
  ***********
  ## Preprocessing
  - Handled missing values by mode imputation.
  - Converted boolean columns to integers.
  - Normalized numerical features using MinMaxScaler.
  - Applied label encoding and one-hot encoding as needed.
    *************
    ## Models Used
    - K-Nearest Neighbors (KNN)
    - Logistic Regression
    - Naive Bayes
    - Decision Tree
    - Random Forest
      ***********
      ## How to Run
      - Load the original dataset from the Data folder.
      - Run preprocessing scripts.
      - Train the models and generate predictions.
      - Check prediction files in Data/Result for evaluation.
      

