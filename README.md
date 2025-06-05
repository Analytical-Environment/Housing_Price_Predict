# 🏠 Housing_Price_Predict 🏠

This ```notebook``` aims to conduct a comprehensive analysis of the Colombian real estate sector, conducting the following study:

## 1. Data curation techniques, null data handling, and outlier management.
## 2. Statistical analysis, distribution fitting, and calculation of statistical moments, as well as trends in the system's macrostate variables.
## 3. Predictive models such as Random Forest and Deep Learning to predict the value of homes, both for rent and for sale, based on the system's macrostate variables.

The database can be found on [Kaggle](https://www.kaggle.com/) by clicking on [Houses](https://www.kaggle.com/datasets/julianusugaortiz/colombia-housing-properties-price).

## Conclusions

The behavior of property price distributions, including characteristics such as bathrooms, bedrooms, type of operation, and apartments, was determined, showing that sales prices follow a beta distribution.

The neural network was determined to be the best predictive model, with a slightly higher MAE value than random forests; however, the computational cost was much lower, with a total of 30 and 5 minutes, respectively.

A positive dependence of price on the number of bedrooms and bathrooms is evident, and factors such as geographic location show behavior that suggest price influences location. The total area does not show much relevance in the prediction model; however, this may be due to the techniques used in data curation.
