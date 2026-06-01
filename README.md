# 🏡 Real Estate Predictive Regression Model

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24+-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.2+-150458.svg)

## 🎯 Overview
A machine learning pipeline engineered to forecast real estate valuations based on multidimensional housing data. This project demonstrates end-to-end data processing, from initial exploratory data analysis (EDA) to feature engineering and predictive modeling.

## 📊 Dataset & Features
* **Data Source:** Ames Housing Dataset (Kaggle)
* **Key Features:** Overall Quality, Above Ground Living Area, Total Square Footage
* **Target Variable:** Property Sale Price 

## 🧠 Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib / Seaborn
* **Modeling:** scikit-learn (Random Forest Regressor)

## 🚀 Execution
1. Clone the repository:
   git clone [https://github.com/Divyanshu10045/real-estate-price-predictor.git](https://github.com/Divyanshu10045/real-estate-price-predictor.git)

2. Install the required dependencies:
   pip install -r requirements.txt

3. Run the Jupyter Notebook to view the EDA and model training:
   jupyter notebook notebooks/01_eda_and_cleaning.ipynb

## 🏆 Results & Performance
* Engineered custom architectural features (TotalSF) that ranked among the top 3 most important predictive variables.
* Successfully explained 85%+ of price variance using an ensemble Random Forest model.
