
# Traffic Crash Severity Prediction 🚗💥  

## 📌 Overview  
This project predicts **traffic crash severity** using machine learning techniques on the **Chicago Traffic Incident Dataset**. The goal is to assist city planners and policymakers in reducing severe crashes through data-driven insights.  

## 📂 Project Structure  
- `DataPioneersFinalProject.ipynb` → Jupyter Notebook with ML model training & evaluation  
- `Traffic_Crashes_-_Crashes_20241104.csv` → Raw dataset used for training  
- `DataPioneersProjectReport.pdf` → Final project report with methodology & results  
- `DataPioneersFinalProject.html` → Databricks analysis export  

## 🚀 Technologies Used  
- **Python**, **Scikit-Learn**, **XGBoost**, **Random Forest**, **Logistic Regression**  
- **SMOTE** for handling class imbalance  
- **PySpark** for big data processing  
- **Tableau** for visualization  

## 📊 Key Results  
- **XGBoost Model:** 84% accuracy, 78% recall for severe crashes  
- **Random Forest:** 81% accuracy, 70% recall for severe crashes  
- **Feature Importance:** Weather, time of day, road conditions significantly impact severity  

## 🔧 Setup & Installation  
1. Clone this repo:  
   ```sh
   git clone https://github.com/your-username/Traffic-Crash-Analysis.git
   cd Traffic-Crash-Analysis