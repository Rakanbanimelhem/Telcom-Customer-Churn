# Telcom-Customer-Churn

## Introduction: This project involves solving a binary classification machine learning problem in the Telecommunication industry.

## Aim: The aim of this project is to make accurate predictions from historical data in regards to whether a Telecommunication customer will churn or not.

## Methodology: While the fine details of the methodology followed in this project will be elaborated further in the relevant sections to come, it is to be mentioned that 16 machine learning models with optimized 12 machine learning models have been implemented, compared, and contrasted to identify the best-performing one.

### 01. Import CPU Python Libraries 
### 02. Function Helper
### 03. Import Dataset & Data Description
        - Import CSV File
        - Data Description
### 04. Data Understanding
        - Data Information
        - Data Summary Statistic
        - Data Variance
### 05. Select the Featurs
### 06. Data Pre-Processing
        - Drop Variables 
        - Convert Data Type
        - Missing Value
### 07. Exploratory Data Analysis
        - DV Visualization
        - Categorical IDV
        - Categorical IDV With DV
        - Numerical IDV
        - Numerical IDV With DV
### 08. Data Transformation
        - Stander Scale
### 9. Feature Selection
        - Wrapper - Forward
### 10. Feature Engineering 
        - LableEncoder
### 11. Statistics
        - Correlations IDV with DV
        - Correlation between all the Variables
### 12. Resampling Data
        - SMOTE
### 13. Data Splitting 
### 14. Standard Machine Learning Models 
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Naive Bayes Classifiers
        -        Naive Bayes Classifier for Multivariate Bernoulli
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        XGBoost Classifiers
        -        Support Vector Machines Classifiers
        -        Linear Support Vector Classification
        -        Multilayer Perceptron Classifier
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
### 15. Optmization Machine Learning Models 
        - random grid for CPU Machine Learning Models
        - Hyperparameters for CPU Machine Learning Models
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        Support Vector Machines Classifiers
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
### 16. Accuracy Score Summary 

## Results: 

The results for the Optimization Machine Learning it is showing Histogram-based Gradient Boosting Classification Tree, Gradient Boosting Classifier, K Neighbors Classifier with accuracy (83.2, 82.3, 81.5) respectively.

![stml](https://user-images.githubusercontent.com/82437810/175177484-7d360986-37aa-47db-9da9-9ce3427a1e7c.png)

![newplot](https://user-images.githubusercontent.com/82437810/175177489-363b8d20-3acb-4f78-8636-8f6b429d6c64.png)

The results for the Optimization Machine Learning it is showing Histogram-based Gradient Boosting Classification Tree, Gradient Boosting Classifier, K Neighbors Classifier with accuracy (83.2, 82.3, 81.5) respectively.

![opml](https://user-images.githubusercontent.com/82437810/175177696-f62a294b-75b7-454a-945c-19e2aef468a2.png)

![newplot](https://user-images.githubusercontent.com/82437810/175177708-486898d0-60c9-4b9e-b4ab-e6c87e250a9a.png)

## Discussion:

As it can be seen above, the performance of some of the models have in fact reduced even after going through the process of optimization. This is because the hyperparameters have been experimented with only 150 interations. This iteration number is chosen at random, instead of the default number of optimization. Although performance or accuracy of the models could have been further improved than the original accuracies of the models, the computation power and time required to carry out the entire learning process is more than ideal. Since the highest accuracy achieved is 83.2%, this has been deemed sufficient for the purpose of this project and not further experimentation have been performed in attempts to achieve high accuracy.

Accuracy Standered CPU Models vs Accuracy Optimization CPU Models. as it is showing 'Histogram-based Gradient Boosting Classification Tree', 'Gradient Boosting Classifier', 'K Neighbors Classifier', 'AdaBoost Classifier', 'Stochastic Gradient Descent Classifier', 'Linear Perceptron Classifier' the accuracy increased between 1% and 11%.

![Screenshot 2022-06-23 073949](https://user-images.githubusercontent.com/82437810/175177804-e42df853-7f2a-4b01-95f8-b7952aa4d0c8.png)
