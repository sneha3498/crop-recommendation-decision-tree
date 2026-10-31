# crop-recommendation-decision-tree
# Crop Recommendation System using Decision Tree

A machine learning mini project that recommends the most suitable crop
based on soil nutrients and weather conditions.

## Problem
Predict the best crop (22 classes) from 7 inputs: N, P, K,
temperature, humidity, pH and rainfall.

## Dataset
- File: `Crop_recommendation.csv` (Kaggle: Crop Recommendation Dataset)
- 2,200 rows, 22 crops, 100 rows per crop (balanced), no missing values

## Algorithm
Decision Tree Classifier (Scikit-learn), criterion = gini, max_depth = 8

## Results
- Test accuracy: **97.27%**
- Most important features: rainfall, phosphorus, humidity
- Mistakes were mostly between similar crops (rice/jute, mothbeans/lentil)

## Files
- `Crop_Recommendation_Decision_Tree.ipynb`: full code with outputs
- `Crop_recommendation.csv`: dataset
- `Crop_Recommendation_ML_Project.pptx`: project presentation

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

## Author
Sneha Kumari | Subject: Machine Learning
Submitted to: Miss Ashna Kushwaha
