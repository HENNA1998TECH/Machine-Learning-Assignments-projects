## Machine-Learning-Assignments-projects
# Assignment 1: Statistical Measures
You are given house_price.csv which contains property prices in the city of Bangalore. You need to examine price per square feet do the following:

Q1. Perform basic EDA (Score:1)

Q2. Detect the outliers using following methods and remove it using methods like trimming / capping/ imputation using mean or median
a) Mean and Standard deviation
b) Percentile method
c) IQR(Inter quartile range method)
d) Z Score method

Q3. Create a box plot and use this to determine which method seems to work best to remove outliers for this data? 

Q4. Draw histplot to check the normality of the column(price per sqft column) and perform transformations if needed. Check the skewness and kurtosis before and after the transformation.

Q5. Check the correlation between all the numerical columns and plot heatmap.

Q6. Draw Scatter plot between the variables to check the correlation between them. 


# Assignment 2: EDA and Preprocessing
Objective: The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Data Exploration: Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns.

Data Cleaning:  Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers. Replace the value 0 in age as NaN Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode)

Data Analysis: Filter the data with age >40 and salary<5000 Plot the chart with age and salary Count the number of people from each place and represent it visually

Data Encoding:  Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.

Feature Scaling: After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler.



# Assignment 3: Regression 
Objective:
 The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset.

Dataset:
Use the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.

Key Components to be Fulfilled:
Loading and Preprocessing :


Load the California Housing dataset using the fetch_california_housing function from sklearn.
Convert the dataset into a pandas DataFrame for easier handling.
Handle missing values (if any) and perform necessary feature scaling (e.g., standardization).
Explain the preprocessing steps you performed and justify why they are necessary for this dataset.


Regression Algorithm Implementation:
 Implement the following regression algorithms:


Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
 For each algorithm:
Provide a brief explanation of how it works.
Explain why it might be suitable for this dataset.


Model Evaluation and Comparison :
Evaluate the performance of each algorithm using the following metrics:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared Score (R²)
Compare the results of all models and identify:
The best-performing algorithm with justification.
The worst-performing algorithm with reasoning.

# Assignment 4:Classification Problem
Objective:
The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.

Dataset:
Use the breast cancer dataset available in the sklearn library.

Key components to be fulfilled:

1. Loading and Preprocessing 
Load the breast cancer dataset from sklearn.
Preprocess the data to handle any missing values and perform necessary feature scaling.
Explain the preprocessing steps you performed and justify why they are necessary for this dataset.

3. Classification Algorithm Implementation 
Implement the following five classification algorithms:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. k-Nearest Neighbors (k-NN)
For each algorithm, provide a brief description of how it works and why it might be suitable for this dataset.

3. Model Comparison 
Compare the performance of the five classification algorithms.
Which algorithm performed the best and which one performed the worst?


