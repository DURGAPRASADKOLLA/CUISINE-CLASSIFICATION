# CUISINE-CLASSIFICATION
1)Project Overview : 
This project builds a multiclass classification model to predict the primary cuisine type of a restaurant based on various features such as cost, location, availability of services, and ratings.
The classification can assist in categorizing restaurants, recommending cuisines in new areas, or auto-tagging listings based on their attributes.

2)Dataset Summary : 
The dataset includes the following relevant features:
Restaurant name and location (city, locality)
Cuisines offered (multi-label, simplified to first cuisine)
Price range and average cost for two
Aggregate rating
Online delivery and table booking availability
Geographical coordinates (latitude and longitude)

3)Problem Definition : 
Type: Multiclass Classification
Target: First listed cuisine from the Cuisines column
Examples: "North Indian", "Chinese", "Italian", etc.

4)Project Steps : 

A)Data Preprocessing : 
Handled missing values in the Cuisines column
Simplified multi-cuisine entries by taking the first cuisine
Encoded target labels using Label Encoding
One-hot encoded categorical features like city and delivery options

B)Model Training :
Split the dataset into training and testing sets (80/20)
Trained a Random Forest Classifier
(Optional: Try other models like Logistic Regression, XGBoost, etc.)

C)Evaluation : 
Metrics used: Accuracy, Precision, Recall, F1-score
Evaluated using a classification report on the test set
Filtered only the labels present in the test set to avoid mismatches

5)echnologies Used : 
Python
Pandas and NumPy (data manipulation)
Scikit-learn (modeling and evaluation)
Matplotlib/Seaborn (optional: performance visualization)
