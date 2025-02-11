# Data-Engineering
This integration helps Experiments provide more targeted health and wellness recommendations and improve supplement formulations.

1001-Experiments currently has the following four datasets with four months of data:

"user_health_data.csv" which logs daily health metrics, habits and data from wearable devices,
"supplement_usage.csv" which records details on supplement intake per user,
"experiments.csv" which contains metadata on experiments, and
"user_profiles.csv" which contains demographic and contact information of the users.
Each dataset contains unique identifiers for users and/or their supplement regimen.
# Project Goal
The goal of this project is to write a Python function that cleans and merges these datasets into a single dataset. The final dataset should provide a comprehensive view of each user's health metrics, supplement usage, and demographic information.

# How to run the code

To test the code, run only the code merge_all_data('user_health_data.csv', 'supplement_usage.csv', 'experiments.csv', 'user_profiles.csv')
The merge_all_data function must return a DataFrame, with columns as described below.
All columns must accurately match the descriptions provided below, including names.
