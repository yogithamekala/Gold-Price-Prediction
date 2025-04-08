Gold Price Prediction Using Machine Learning
This repository contains the code and workflow behind a machine learning project focused on predicting gold prices (GLD) using related market indicators. The full explanation, including reasoning behind modeling choices and data handling decisions, is available on my [blog](https://www.blogger.com/u/2/blog/post/edit/1907108883869461564/8173960492873683240)
Overview
Predicts gold prices using features like SPX, USO, SLV, and EUR/USD

Uses Random Forest Regressor from sklearn

Achieved 0.98 R² Score on test data

Dataset
CSV file with 2,290 rows and 7 columns

Target: GLD (Gold price)

Features: SPX, USO, SLV, EUR/USD

Date column dropped during training

Tools
pandas, numpy for data handling

seaborn, matplotlib for visualization

sklearn for modeling and evaluation

