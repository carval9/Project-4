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
1. **Review Feature Importances**
2. **Hyperparameter Tuning**
3. **Data Normalization**

## Prediction
### Price Prediction Example

## Usage Instructions
Download all the files and place them in a folder together with the same name. Adjust the directions to pull the model, Java, data, and HTML with a local host so you can use the web page installed. Run in Python and use a browser to navigate the tool that provides car price predictions.

## Difficulties
Some difficulties encountered during the creation of this project included finding a suitable dataset. Initially, we used a dataset from India that worked fine with logistic regression, but the random forest did not work well with linear regression. Due to the lack of knowledge of the Indian market, this dataset was deemed unsuitable.

The second dataset we found had fewer columns but was very large (820K rows * 9 columns), making it difficult to work with in Google Colab and Visual Studio. For the scope of this project, we found a third dataset with 2.6k rows and more than 100 columns, resulting in better R² and model accuracy.

![Model Accuracy](path/to/accuracy/image.png)

This is why this dataset was chosen.

## Database Information
The dataset was obtained from the following page: [Kaggle Dataset](https://www.kaggle.com/datasets/tymekurban/new-cars-usa-202223-dataset). The dataset is free to use, run, and modify.

## Authors
- **Daniel Bardan** (@Wynton0535)
- **Rodrigo Figueroa** (@RoFigueroa18)
- **Pablo Morales** (@PabloUMD)
- **Carlos Valencia** (@carval9)
- **Jose Franco** (@jrobertofg)
