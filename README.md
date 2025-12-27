# Student Depression Prediction with Explainable AI (XAI)
# 🎓 Student Depression Prediction with Explainable AI (XAI)

## 📌 Project Overview
Mental health is a critical concern in academic environments. This project builds a machine learning pipeline to predict depression in students based on various lifestyle and academic factors. Beyond just making predictions, this project focuses on **Explainability** and **Statistical Validation** to ensure the model is reliable and transparent for healthcare applications.

## 🚀 Key Features
* **High Performance:** Achieved **84.2% Accuracy** using Logistic Regression.
* **Data Science Pipeline:** Includes comprehensive EDA, data cleaning, and feature scaling.
* **Explainable AI (XAI):** * **SHAP (Global):** Used to understand which factors (like Financial Stress) drive depression across the entire dataset.
    * **LIME (Local):** Used to explain exactly why a specific individual student was flagged by the model.
* **Statistical Validation:** Verified results using P-values, 5-Fold Cross-Validation, and 95% Confidence Intervals.

## 📊 Dataset
The dataset contains information about students including:
* Academic Pressure & Study Satisfaction
* Sleep Duration & Dietary Habits
* Financial Stress
* Family History of Mental Illness

## 📈 Results & Evaluation
* **Accuracy:** 84.26%
* **F1-Score:** 0.87 (for the Depressed class)
* **Stability:** Cross-validation confirmed the model is stable and generalizes well to new data.



## 🛠️ Technologies Used
* **Language:** Python
* **ML Libraries:** Scikit-learn, Pandas, NumPy
* **XAI Tools:** SHAP, LIME
* **Statistics:** Statsmodels
* **Visualization:** Matplotlib, Seaborn

## 📂 How to Run
1. Upload the `Healthcare (2).ipynb` file to Jupyter Notebook or Google Colab.
2. Ensure you have the dataset `.csv` file in the same folder.
3. Run all cells to see the results and visualizations.
