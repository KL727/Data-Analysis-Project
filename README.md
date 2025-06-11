# Data-Analysis-Project
# IMDB Box Office Prediction

## Overview
This is a course project for COMP_SCI_7209 (Big Data Analysis and Project), where I explored different models to predict the global box office revenue of movies listed on IMDB. The dataset comes from a Kaggle competition and includes features like cast, crew, budget, genre, release date, etc.

## What I Did
- Cleaned and preprocessed the data (handled missing values, outliers, feature formatting)
- Performed exploratory data analysis (EDA) to understand feature distributions and correlations
- Built and compared several regression models: Random Forest, XGBoost, Ridge, and Lasso
- Evaluated models using RMSE and selected the best-performing one

## Results
Random Forest gave the best performance with the lowest RMSE (~2.09), followed by XGBoost. Ridge and Lasso performed less well on this dataset.

## Files
- `IMDB_BoxOffice_Prediction.ipynb`: Main Jupyter notebook with all code and analysis
- `report.pdf`: Final written report submitted for the course
- `sample_submission.csv`: Provided by Kaggle for submission format reference

> ⚠️ Note: Due to file size and licensing, `train.csv` and `test.csv` are not included.  
> You can find the dataset on [Kaggle](https://www.kaggle.com/) under “IMDB Box Office Prediction” (competition name may vary).

## Author
Kengtian Lu  
MSc Computing and Innovation  
University of Adelaide
