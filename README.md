# Bike-sharing-demand-prediction ML Regression
![image](https://github.com/MDRIZWANKHAN/Bike-sharing-demand-prediction/assets/125923064/b7c4ce89-c1eb-4b58-9a2b-12fd76c33b9b)

Bike Sharing Demand Prediction - Regression

### **Project Summary**
A bike-sharing system provides people with a sustainable mode of transportation and has beneficial effects for both the environment and the user. In recent days, Pubic rental bike sharing is becoming popular because of is increased comfortableness and environmental sustainability. Data used include Seoul Bike and Capital Bikeshare program data. Data have weather data associated with it for each hour. For the dataset, we are using linear regression model were train with optimize hyperparameters using a repeated cross validation approach and testing set is used for evaluation. Multiple evaluation indices such as Mean squared error , Root Mean Square error, r2 score,adjusted r2 score are use to measure the prediction performance of the regression models.


### **Problem Statement**
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

The main objective is to make predictive model, which could help them in predicting the bike demands proactively. This will help them in stable supply of bike wherever needed.

### ***Approaches***
we will break this endeavor into different parts-:
### ***EDA***
- In this i have created different charts like Bar, Kde, Histogram, Box, Heatmap and Pair Plot for getting insights from the data and based on that we can do some feature Engineering.
- I also performed Hypothesis Testing based on our findings.
### ***Feature Engineering & Data Pre-processing***
- In this i Handled Missing Values, Outliers, Categorical Encoding.
- Performed Feature Manipulation to minimize feature correlation and create new features.
- Applied VIF to avoid avoid overfitting.
- VIF value greater than 5 or 10 is considered to be high levels of multicollinearity, and variables with high VIF values may need to be removed from the model to improve its accuracy.
- ***Data Transformation*** i used log transformation to transform data because in some of the columns our data is positively skewed and for positively skewed lof transformation is used.
- ***Data Scaling*** I used MinMaxScaler.
- MinMaxScaler is a popular feature scaling technique used to transform numerical features to a common scale. It scales the features to a fixed range (usually between 0 and 1) based on the minimum and maximum values of the features.
- ***Data Splitting*** I used 80:20 data splitting ratio.
- When we split our data into training and test sets, we're essentially creating two different datasets that we can use to test our model's performance. This can help us identify any issues with our data, such as outliers or missing values, and make our model more robust to these issues.
  
### ***ML Model Implementation***
***ML Model - 1- Implemented Linear Regression***
 - 
