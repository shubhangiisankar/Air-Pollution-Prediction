# Air Pollution Prediction

## Project Overview

This project predicts **PM2.5 air pollution levels** using machine learning techniques.
Air pollution is a serious environmental and public health issue, and predicting pollution levels helps governments and citizens take preventive actions.

The model is trained on historical air quality data containing various pollutants such as **PM10, NO, NO2, NOx, CO, SO2, O3**, along with time-based features.

---

## Problem Statement

Cities need systems that can **predict air quality levels in advance** so that authorities can issue warnings and protect public health.

This project focuses on predicting **PM2.5 concentration**, one of the most harmful air pollutants.

---

## Dataset

Dataset used in this project:

https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

The dataset contains pollution data from multiple cities with features such as:

* PM2.5
* PM10
* NO
* NO2
* NOx
* NH3
* CO
* SO2
* O3
* AQI

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Correlation Analysis
6. Feature Engineering (Year, Month, Day)
7. Model Training
8. Model Evaluation

---

## Machine Learning Models

### Linear Regression

Used as the baseline model.

Results:

* MAE: 19.47
* RMSE: 40.66
* R² Score: 0.61

### Random Forest Regressor

Used to improve prediction accuracy.

Results:

* MAE: 14.54
* RMSE: 31.81
* R² Score: 0.76

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

Air-Pollution-Prediction
│
├── data
│   └── city_day.csv
│
├── notebooks
│   └── EDA.ipynb
│
├── air_pollution_model.pkl
├── requirements.txt
└── README.md

---

## Future Improvements

* Use advanced models like **XGBoost or LSTM**
* Predict pollution levels for future days
* Deploy the model as a web application
* Build a real-time pollution monitoring dashboard
