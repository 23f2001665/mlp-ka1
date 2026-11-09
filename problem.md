# KA1

## DATASET DESCRIPTION

The dataset requires you to make predictions on the price of a flight ticket given a set of features. The features are listed below.
Files

-   train.csv - The training set which contains the features and the target
-   test.csv - The test set for which the target column is hidden
-    sample_submission.csv - A sample submission file in the correct format

Column Description

-    airline: Name of the Airline company
-    flight: Information about flight code
-    source: City from which the flight takes off
-    departure: Time period at which the flight takes off
-    arrival: time period at which the flight lands
-    destination: City where the flight lands
-    class: Information about seat class
-    duration: Overall time taken to travel between cities in hours
-    days_left: Number of days between booking and trip dates
-    price: Information about ticket price

## Assignment Description

Assignment 1

The dataset requires you to make predictions on the price of a flight ticket given a set of features. You will be provided with a training dataset and a test dataset. The labels for the test dataset will remain hidden and your task is to submit predictions for the same. The assignment will be conducted on the Kaggle Platform
Instructions

    Use the following link to join the competition : https://www.kaggle.com/t/ab9188863aae471c8292dc87d0cad7b5

    After joining the competition, go to the Code tab and create a New Notebook.

    Mandatorily fill the form present in the portal titled Kaggle Assignment Registration by Nov 11 else the assignment will not be awarded any marks.

    Use this Notebook to make model submissions and the performance of the model will be reflected in the leaderboard.

    Refer the rubrics provided below for the peer review to understand the minimum requirements in the notebook

    The deadline for the assignment is Nov 11 2026 11pm.

    Provide a walkthrough of your notebook through video recording describing the different methods used and insights obtained (keep it under 8 - 12 mins). Upload the recording to google drive and provide the link in the submission tab. Ensure view access is provided to the video file to everyone.

    Refer the link for more details on submission and peer review: https://docs.google.com/document/d/e/2PACX-1vS1VeHBjpb4ksp4lfYXTE2V7s7Yc8hF86wbEJIojv8sKVthFhrZsqx7LEXcjPN4Mkc_EDA6mv3RBGpH/pub

Peer Review Rubrics

Criteria
	

Weight
	

Absent (0 point)
	

Present (1 point)

Identify data types of different columns
	

5
	

No information data types provided
	

The data types of the different columns are identified and explicitly stated in the notebook

Present descriptive statistics of numerical columns
	

5
	

Required details regarding numerical columns is not provided
	

Details such as min value, max value, mean and median for each numerical column is presented

Identify and handle the missing values
	

10
	

No information regarding missing values provided
	

Missing values are identified and are dropped or imputed

Identify and handle duplicates
	

10
	

No information regarding duplicates provided
	

Duplicates are identified and are dropped if they exist

Identify and handle outliers
	

10
	

No information regarding outliers provided
	

Outliers are identified and explanation for retaining / dropping is provided

Present at least three visualizations and provide insights for the same
	

10
	

Less than three visualizations present
	

At least three visualizations on the data is presented 

Scale Numerical features and Encode Categorical features
	

10
	

No information regarding scaling and encoding of variables
	

Explanation for scaling (or not scaling) and encoding (or not encoding) is provided

Model Building (at least 7)
	

20
	

Lesser than 7 different models trained 
	

7 different types of models are trained on the data

Hyperparameter Tuning on any 3 of the models
	

10
	

Lesser than 3 models tuned
	

Hyperparameter tuning is done on 3 of the models

Comparison of model performances
	

10
	

No information regarding comparison of model performance
	

Performance of the models on validation set is compared