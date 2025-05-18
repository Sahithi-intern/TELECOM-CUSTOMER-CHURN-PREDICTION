# 📊 Customer Churn Analysis and Prediction

## 🎯 Objective
Predict customer churn and uncover the key factors driving churn behavior using telecom customer data. This project was developed as part of the **Elevate Labs Phase 2 Internship** to showcase full-stack data analysis, machine learning, and dashboarding skills.

---

## 📂 Dataset
**`Cleaned_churn_dataset.csv`**  
A publicly available telecom churn dataset with:
- **7043 rows**, **21 columns**
- **Target Variable**: `Churn` (Yes/No, ~27% churn rate)
- **Key Features**: `tenure`, `MonthlyCharges`, `Contract`, `InternetService`, `SeniorCitizen`, `PaymentMethod`, etc.
- Cleaned for nulls and converted TotalCharges to numeric
- Irrelevant fields like `customerID` removed

---

## 🧰 Tools & Technologies
- **Python (Google Colab)**: pandas, scikit-learn, seaborn, plotly, xgboost, catboost  
- **Power BI**: Interactive churn dashboard using standard visuals  
- **GitHub**: Project and code repository hosting  
- **SHAP**: Model explainability using SHAP plots

---

## 📁 Project Structure
-->Cleaned_churn_dataset.csv
-->Customer_churn_prediction.ipynb # Colab notebook for preprocessing, ML, evaluation
-->Customer_Churn_Report.pdf # Final 2-page summary report
-->Customer_Churn_Dashboard.pbix # Power BI dashboard file
--> README.md # Project documentation


---

## 🚀 How to Run

### 🧪 Python Notebook
1. Open `Customer_churn_prediction.ipynb` in **Google Colab**
2. Upload `Cleaned_churn_dataset.csv`
3. Run all cells to reproduce:
   - Data cleaning & visualization
   - Machine learning model training (Random Forest, XGBoost, etc.)
   - Performance metrics and SHAP analysis

### 📊 Power BI Dashboard
1. Open `Customer_Churn_Dashboard.pbix` using **Power BI Desktop**
2. Interact with filters: Gender, SeniorCitizen, Contract Type, etc.
3. Analyze churn patterns across different segments


---

## 💡 Insights

- **Tenure < 10 months** is highly associated with churn
- **Month-to-month contracts** show ~45% churn rate vs ~10% for two-year contracts
- **High monthly charges** correlate with increased churn
- **Fiber optic customers** have higher churn vs DSL
- **Over 75%** of churned customers use **Electronic Check** as payment method
- **Model Accuracy**: Achieved ~85% with Random Forest and XGBoost
- **SHAP results** confirm: low tenure, contract type, monthly charges, and internet service as top churn drivers

---

## 📘 Learnings

### ✅ Data Analysis & Visualization
- Applied seaborn and plotly to identify trends in churn behavior
- Explored key relationships with churn using box plots, bar charts, and heatmaps

### ✅ Machine Learning
- Preprocessed data using encoding & scaling
- Evaluated models using accuracy, F1-score, and confusion matrix
- Handled class imbalance (churn = 27%) with appropriate evaluation focus

### ✅ Explainability
- Used **SHAP** to visualize feature impact on churn decisions
- Provided actionable insights to retain at-risk customers

### ✅ Dashboarding
- Created a clean, user-friendly **Power BI dashboard**
- Included slicers for filtering by gender, senior citizen status, and more
- Designed visuals with meaningful business KPIs

---

## 🚧 Challenges Overcome

- Dealt with imbalanced data affecting prediction precision
- Adjusted to Power BI's default visual library without marketplace access
- Tuned hyperparameters to improve model accuracy without overfitting

---





