# HR_Attrition_Prediction
 Predicting Employee Attrition Using Machine Learning &amp; Data Visualization
# 💼 HR Analytics Prediction and Power BI Dashboard

### 🔍 Predicting Employee Attrition Using Machine Learning & Data Visualization

---

## 📘 Project Overview

Employee attrition (or turnover) is a critical challenge for organizations as it impacts productivity, recruitment costs, and long-term performance.  
This project aims to **predict employee attrition** using machine learning techniques and visualize HR insights through an **interactive Power BI dashboard**.

By combining predictive analytics with data visualization, HR managers can make data-driven decisions to reduce employee turnover and improve retention strategies.

---

## 🎯 Objectives

- To predict whether an employee is likely to leave the organization.  
- To analyze the key factors contributing to employee attrition.  
- To visualize attrition trends using **Power BI dashboards**.  
- To provide actionable insights for HR management.

---

## 🧠 Machine Learning Workflow

### 1. **Data Preprocessing**
- Imported HR dataset and handled missing values.  
- Encoded categorical variables using Label Encoding.  
- Split dataset into training and testing sets (80–20 ratio).

### 2. **Model Building**
- Used **Decision Tree Classifier** from Scikit-learn for prediction.  
- Evaluated model performance using accuracy, precision, recall, and F1-score.  
- Applied **SHAP** (SHapley Additive exPlanations) to interpret model behavior.

### 3. **Prediction Export**
- Generated predictions and probabilities for test employees.  
- Saved output as `HR_Attrition_Predictions.csv` for Power BI visualization.

### 4. **Power BI Dashboard**
- Designed an interactive dashboard showing:
  - Attrition Rate by Department, Gender, and Job Role  
  - Salary vs Attrition  
  - Overtime Impact  
  - Key KPIs: Total Employees, Active Employees, Attrition %  
- Added slicers for Department, Education, and Gender for deeper analysis.

---

## 🧰 Tools & Technologies Used

| Category | Tools |
|-----------|-------|
| **Programming Language** | Python |
| **Libraries** | Pandas, NumPy, Scikit-learn, SHAP |
| **Visualization** | Power BI |
| **Development Environment** | Jupyter Notebook |
| **Data Format** | CSV |

---

## 📂 Repository Structure

HR-Analytics-Prediction/
│
├── HR_Attrition_Prediction.ipynb # Model training and evaluation notebook
├── HR_Attrition_Predictions.csv # Final dataset for Power BI
├── HR_Analytics_Dashboard.pbix # Power BI dashboard file
├── hr_data.csv # Input dataset
├── README.md # Project documentation
└── report.pdf # Project summary report

## 🏁 Conclusion

The HR Analytics Prediction project integrates **machine learning** and **data visualization** to deliver actionable HR insights.  
The predictive model identifies employees at risk of leaving, while the Power BI dashboard translates complex HR data into a clear, interactive format — empowering organizations to make data-driven workforce decisions.

---
