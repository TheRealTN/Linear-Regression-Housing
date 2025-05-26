# Linear Regression on California Housing Prices
## 📌 Overview
This project uses linear regression to predict housing prices based on various features such as population, number of bedrooms, and location. The goal is to understand the relationships between these variables and to create a model that can estimate home prices accurately.


## 📑 Dataset Info
This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning and has an easily understandable list of variables.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. The columns are as follows, their names are pretty self explanitory:
- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- median_house_value
- ocean_proximity


## 🧠 Methodology
- Data Cleaning: Removed missing values and insignificant features, and converted categorical variables into numercial data
- Exploratory Data Analysis: Used plots and correlation matrices to understand feature importance
- Modeling: Implemented a multiple linear regression model using scikit-learn
- Evaluation: Assessed model performance using R² score and Mean Squared Error (MSE)

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- Google Colab

## 🔍 Future Improvements
- Try regularized regression (Ridge, Lasso)
- Include more complex models (e.g., Random Forest, XGBoost)
- Convert categorical data using one-hot encoding

