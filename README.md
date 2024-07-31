# Tool to Predict Used Car Prices

## Motivation
The inspiration for this project stems from the need to design a model capable of predicting the prices of used cars. This model can assist customers in determining if they are purchasing a car at a fair price.

## Description
This model utilizes a dataset containing the following features: Price, Year, Mileage, Model, Brand, City, and State. The information is sourced from the United States. The model is trained on machine learning algorithms that iteratively learn with each new piece of data added. A web page with a map interface allows users to input model, year, state, and mileage to receive a price estimate.

## Construction of the Model

### Tools
- Google Colab
- Kaggle
- Visual Studio
- GitHub

### Database Tools
- SQL

### Programming Languages
- HTML
- Java
- Python

### Libraries
- pandas
- numpy
- matplotlib.pyplot
- matplotlib.dates
- sklearn.model_selection
- sklearn.linear_model
- sklearn.ensemble
- xgboost
- sklearn.metrics
- sklearn.model_selection (cross-validation)
- sklearn.preprocessing (PolynomialFeatures, StandardScaler)
- sklearn.cluster (KMeans)
- sklearn.feature_selection (RFE)
- sklearn.impute (SimpleImputer)
- sklearn.pipeline (Pipeline)
- forex_python.converter (CurrencyRates)
- shap
- joblib

## Steps

1. **Import Data**
2. **Import Libraries and Dependencies**
3. **Data Loading**
4. **Data Cleaning**
5. **Exploratory Data Analysis**
6. **Data Splitting**
7. **Advanced Model Training with Random Forest**

## Troubleshooting
- **Step 1:** Review Feature Importances
- **Step 2:** Hyperparameter Tuning
- **Step 3:** Data Normalization
## Prediction
**Price Prediction Example**

## Usage Instructions
Download all the files and place them in a Folder together with the same name adjust the directions to pull the Model, Java, Data and HTML with a local host so you can use the web page installed.
Run in python and with a Browser navigate in the tool that is brought to you to know the price of the cars. 


##Dificulties

Some of the difficulties encounter during the creatin of this project was finding a data set taht would work, that would be fit, First we started with a data set from India, that worked fined with the Log Regression and the random forest did not worked with Linear regression (non of the data sets that were used fit well to this model). When using this Data set we found that the FX transformation to understand better the value of a car was difficult and due to the lack of knowledge of the Indian market and understanding, this made clearly and unvaible data set. 

The second data set we found was smaller in columns, but really big we are talking about 820K rows * 9 columns. which made it really hard to work with in Google colab and visual studio, for the scope of this project. Based on this we foun a 3rd data set with 2.6k Rows and more than 100 columns. which made it a much smaller data set, but with a great result in the R2 and the model accuracy as shown in the following image.  

![image](https://github.com/user-attachments/assets/06f35ae2-4edb-4275-8761-068a8cbd85a8)

This is why this data set was chosen. 

## Database information

Obtained from the following page "https://www.kaggle.com/datasets/tymekurban/new-cars-usa-202223-dataset" the data set is free to use and to run and modify a model. 

## Authors 
**Daniel Bardan** @Wynton0535
**Rodrigo Figueroa** @RoFigueroa18
**Pablo Morales** @PabloUMD
**Carlos Valencia** @carval9
**Jose Franco** @jrobertofg

