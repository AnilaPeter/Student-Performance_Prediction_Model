# Student Performance Prediction Model

This repository contains the implementation of a machine learning project aimed at predicting student performance based on demographic, social, and educational features. The project focuses on predicting final grades in two subjects: Mathematics and Portuguese, using data from the 'student-mat.csv' and 'student-por.csv' datasets.

## Project Overview

The objective of this project is to develop predictive models that estimate students' final grades in Mathematics and Portuguese. We will explore various features, such as family background, study habits, and school-related factors, to analyze how they impact student performance.

The project involves data preprocessing, exploratory data analysis (EDA), feature selection, and the application of machine learning algorithms, such as linear regression, decision trees, and random forest. The results will help identify key factors that affect academic performance, which can offer valuable insights for educators, schools, and policymakers.

## Datasets

The datasets used in this project are sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance):

1. **student-mat.csv**: This dataset contains information on students’ performance in Mathematics, along with other features such as study time, family background, extracurricular activities, and more.
   
2. **student-por.csv**: This dataset contains similar information but focuses on students’ performance in Portuguese.

Both datasets include over 30 features related to students’ personal and academic backgrounds, which are used as input to the prediction models.

## Requirements

To run this project, you will need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Methodology

1. **Exploratory Data Analysis (EDA)**:  
   Perform exploratory analysis on the datasets to understand the distribution of data and the relationships between features and target variables.

2. **Data Preprocessing**:  
   Clean the datasets by handling missing values, encoding categorical variables, and scaling numerical features where necessary.

3. **Feature Selection**:  
   Identify important features that contribute most to predicting the final grades.

4. **Model Building**:  
   Train machine learning models such as Linear Regression, Decision Trees, and Random Forest to predict student performance.

5. **Model Evaluation**:  
   Evaluate the models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² to determine the effectiveness of each model.

## Results

The results from this project will showcase the predictive power of different features and machine learning models in estimating student performance. The key findings will help identify the most influential factors on academic outcomes.
