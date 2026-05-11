# Diabetes Risk Analysis & Prediction 🩺📊

## Overview
This project provides an end-to-end data analysis and machine learning solution to predict diabetes based on patient medical history and demographic data. It combines Python for data processing and modeling with Power BI for interactive data visualization.

## Objectives
* Perform Exploratory Data Analysis (EDA) to find correlations between clinical features (e.g., HbA1c, blood glucose) and diabetes.
* Build a robust Machine Learning model to accurately classify whether a patient has diabetes.
* Create an interactive Business Intelligence dashboard for healthcare insights.

## Tech Stack
* **Programming & Modeling:** Python (Pandas, NumPy, Scikit-Learn, XGBoost)
* **Data Visualization (Python):** Matplotlib, Seaborn, Plotly
* **Business Intelligence:** Power BI

## Model Performance
An **XGBoost Classifier** was trained on the preprocessed dataset, yielding excellent results:
* **Accuracy:** 97%
* **Precision (Class 0):** 97% | **Recall (Class 0):** 100%
* **Precision (Class 1):** 97% | **Recall (Class 1):** 68%
* **F1-Score:** 0.89 (Macro Avg)

## Power BI Dashboards
The project includes an interactive Power BI report with multiple views:
1. **Demographics & Health Conditions:** Analyzes the distribution of patients by age, gender, BMI, and overall diabetes count.
2. **Risk Factors & Lab Results:** Explores the correlation between smoking history, HbA1c levels, blood glucose levels, and specific risk factors like hypertension and heart disease.

<img width="1434" height="802" alt="Screenshot 2025-11-02 223311" src="https://github.com/user-attachments/assets/44c7ee15-d746-4b48-a8a6-c036aaf6ffad" />

<img width="1433" height="801" alt="Screenshot 2025-11-02 223333" src="https://github.com/user-attachments/assets/9fc6e0ed-b126-4968-81a2-c342fe7f3be5" />


## Key Insights
* Patients with elevated HbA1c and blood glucose levels show a significantly higher likelihood of diabetes.
* Age and BMI are strong contributing factors, with the 51-70 age group showing notable risk patterns.
* The presence of multiple risk factors (hypertension + heart disease) increases the probability of a positive diabetes diagnosis.

## How to Run
1. Clone the repository: `git clone <your-repo-link>`
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to view the EDA and model training process.
4. Open the `.pbix` file in Power BI Desktop to interact with the dashboard.
