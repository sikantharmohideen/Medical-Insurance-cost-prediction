# MEDICAL INSURANCE COST PREDICTION

![doc](https://user-images.githubusercontent.com/95271427/156216091-76460dd9-e607-4561-910b-d5368f3befa4.gif)

To predict things have been never so easy. I used to wonder how Insurance amount is charged normally. So, in the mean time I came across this dataset and thought of working on it! Using this I wanted to know how few features determine our insurance amount! This is a simple regression project.

## DATASET

Data source : https://www.kaggle.com/mirichoi0218/insurance

Column Attributes :

1. age: age of primary beneficiary
2. sex: insurance contractor gender, female, male
3. bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
4. children: Number of children covered by health insurance / Number of dependents
5. smoker: Smoking
6. region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest


## PROJECT OVERVIEW
• Seek insight from the dataset with Exploratory Data Analysis

• Performed data processing, data engineering to prepare data before modeling

• Built a model to predict Insurance Cost based on the features


## FEATURES
1. Exploring the dataset
2. Converting Categorical values to Numerical
3. Plotting Heatmap to see dependency of Dependent valeu on Independent features
4. Data Visualization (Plots of feature vs feature)
5. Data Preparation
6. Prediction using Linear Regression
7. Prediction using SVR
8. Prediction using Ridge Regressor
9. Prediction using Random Forest Regressor
10. Predction using Lasso Regressor
11. Prediction using XGB Regressor
12. Comarative Analysis
13. Plotting Graph for all Models to compare performance

## LIBRARIES USED
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Sklearn

## MODELS USED

1. Linear Regression
2. SVM
3. Ridge Regression
4. Random Forest Regressor
5. Lasso Regressor
6. XGB Regressor

## DATA VISUALISATION

## Correlation plot
![Correlation](https://user-images.githubusercontent.com/95271427/156747322-3fabc277-35bd-41bf-b78a-68ed89265244.png)


## Distribution of charges
![Charges dist plot](https://user-images.githubusercontent.com/95271427/156747225-73cd33a0-f09c-441d-b948-5c69aece95a7.png)

## Pair plot
![pair plot](https://user-images.githubusercontent.com/95271427/156747375-efa85f77-f2ac-4491-b99a-9fb36a0b17e3.png)


## PERFORMANCE MATRIX

## 1. Mean Absolute Error

![MAE](https://user-images.githubusercontent.com/95271427/156746890-9a2a9bce-4cf4-4846-9896-7e7e52763adb.png)

## 2. Mean Squared Error

![MSE](https://user-images.githubusercontent.com/95271427/156746971-0e97d233-ec6c-41a5-8649-53716b62ffcd.png)

## 3. Root Mean Squared Error

![RMSE](https://user-images.githubusercontent.com/95271427/156747012-cb365ab3-85e4-4e07-ab97-18e851f980d4.png)

## RESULT


![CA result](https://user-images.githubusercontent.com/95271427/156746469-0b3cb0a2-07d0-4889-86d9-4da28d061f18.png)

Hence we can conclude that Random Forest Regression is performing high with 89%



