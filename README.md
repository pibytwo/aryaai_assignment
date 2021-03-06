# Assignment
This is the Assignment for the post of Data Scientist at Arya.ai

Objective - To carry out binary classification on provided data

General Approach
1. Data collection
2. Data preprocessing
3. Feature engineering
4. Scaling/Normalization
5. Model selection
6. Training
7. Validation
8. Testing
9. Deployment



Thought process - 
1. Load the training dataset from csv file and figure out what kind of information is present in it.
2. Divide the dataset in features and classes dataframe
3. Check for missing data and handle it
4. Perform EDA
5. Find out the correlation between multiple features present in dataset
5. Feature selection using suitable technique
6. Scaling/Normalization of training data
7. Dimension reduction if required
8. Selection of classifier
9. Training and cross validation of classifier
10. Performance metrics of trained model
11. Prediction on test dataset

Pipeline
1. First run 'feature_selection.ipynb' notebook to check whether some features are needed to be removed
2. To check if dimension reduction is required or not run 'dimension_reduction.ipynb' notebook
3. Finally, to carry out complete machine learning pipeline run 'complete_pipeline.ipynb' notebook
4. After successful execution of above steps 'output.csv' file will be generated with predictions on test dataset

Requirements
1. Python >= 3.7
2. python library information is available in 'requirements.txt'