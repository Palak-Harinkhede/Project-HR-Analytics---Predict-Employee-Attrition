# HR Attrition Analysis

## 📌 Project Overview

Employee attrition is a major concern for organizations, impacting productivity, employee morale, and continuity. This project analyzes historical HR data to identify the key factors behind attrition and predict potential employee resignations. The analysis incorporates machine learning, SHAP explainability, and interactive visualizations to support HR in developing data-driven retention strategies.

---

## 🎯 Objectives

- Explore and clean HR data to uncover attrition trends.
- Build a predictive model to identify at-risk employees.
- Use SHAP to interpret model outputs.
- Create an interactive Power BI dashboard for stakeholders.
- Recommend actionable insights to HR teams.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, Scikit-learn, Seaborn, Matplotlib)
- **Power BI**
- **Google Colab**
- **SHAP (SHapley Additive Explanations)**
- **Dataset Source:** IBM HR Analytics

---

## 🔄 Project Workflow

1. **Data Loading & Cleaning**
   - Loaded the IBM HR dataset.
   - Removed irrelevant features and handled categorical encoding.

2. **Exploratory Data Analysis (EDA)**
   - Visualized attrition trends by department, job role, age, and satisfaction levels.
   - Highlighted patterns in overtime and tenure.

3. **Model Building**
   - Used Logistic Regression for binary classification (Attrition vs. No Attrition).
   - Evaluated model performance using accuracy and confusion matrix.

4. **Model Interpretation**
   - Applied SHAP to explain the impact of each feature on predictions.

5. **Dashboard Creation**
   - Built an interactive Power BI dashboard with filters by department, age group, job role, etc.

6. **Report & Recommendations**
   - Summarized findings in a professional report.
   - Suggested data-driven strategies for employee retention.

---

## 📊 Key Insights

- **Overtime** is the strongest predictor of attrition.
- **Sales** and **R&D** departments face higher attrition rates.
- Employees aged **18–25** are more prone to resignation.
- **Low job and environment satisfaction** is strongly linked to attrition.
- **Longer tenure with the same manager** is associated with retention.

---

## 📁 Deliverables

- [✅ Raw Dataset](./WA_Fn-UseC_-HR-Employee-Attrition.csv)
- [✅ Processed Dataset](./processed_hr_data.csv)
- [✅ Power BI Dashboard (.pbix)](./HR_Attrition_Dashboard.pbix)
- [✅ Final Report (PDF)](./HR%20Analytics%20Report.pdf)

---

## 📌 Conclusion

This project successfully demonstrates how data analytics and machine learning can be used to understand and predict employee attrition. With SHAP-based explainability and Power BI visualizations, HR departments can proactively address issues that lead to employee turnover.

---


## 🚀 Future Enhancements

- Real-time attrition monitoring.
- Integration with internal HRMS tools.
- Enhanced feature engineering with employee survey data.
