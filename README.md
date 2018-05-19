# Getting-and-Cleaning-Data-Course-Project
This consists of run_analysis R script which basically does the following
1. Downloads the dataset if not present in the current working directory
2. Loads all the information and activity features into the current sessin 
3. Loads both the training and test datasets, keeping only those coloumnswhich reflect a mean or a standard deviation
4. For each dataset, loads the activity and subject data and merges those coloumns with the dataset
5. Merges the datasets and convers activity and subject coloumns into factors
6. Creates a tidy dataset that consists of the average value of each variable for each subject and activity pair.

Contains a code file describing the information regarding these variables

