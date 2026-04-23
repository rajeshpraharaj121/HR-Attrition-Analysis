# 👔 Advanced HR Attrition Analysis

## 📌 Project Overview
This project performs an advanced analysis of employee data to uncover the key drivers behind employee turnover. 

Moving beyond standard exploratory data analysis, this project employs a **problem-solution framework** to deliver actionable HR interventions. Furthermore, it leverages **Machine Learning** to accurately predict attrition risk and rank the most critical factors influencing an employee's decision to leave.

---

## 🛠️ Tools & Technologies
- **Python**: Core programming language
- **Pandas & NumPy**: Data manipulation and cleaning
- **Scikit-Learn**: Machine Learning (Random Forest Classifier)
- **Seaborn & Matplotlib**: Advanced, stylish data visualization

---

## 🧠 Machine Learning: Random Forest Model
We implemented a robust `RandomForestClassifier` to predict whether an employee will stay or leave.
- **High Accuracy**: The model achieves ~87% accuracy in identifying attrition risk.
- **Feature Importance**: Rather than guessing why employees leave, the model definitively ranks the top drivers. Key factors identified include Monthly Income, Age, and Overtime. This allows HR to transition from a reactive approach to a **proactive retention strategy**.

---

## 💡 Key Insights & Solutions

- **The Income & Age Factor**: Attrition is heavily clustered among younger employees (under 30) making lower monthly incomes.
  - *Solution*: Implement clear career progression pathways and review entry-level compensation packages to retain young talent.
- **The Overtime Problem**: Employees working overtime show significantly higher attrition compared to those who do not.
  - *Solution*: Monitor overtime hours closely and consider hiring temporary staff during peak seasons to prevent burnout.
- **Departmental Risk**: The Sales department exhibits a disproportionately high turnover rate.
  - *Solution*: Conduct targeted stay-interviews within the Sales team to address specific job pressures, quota structures, and commission plans.

---

## 📈 Visualizations
The project features highly visible, presentation-ready visualizations, including:
- Interactive-style scatterplots for Income vs. Age
- Stacked bar charts for Overtime impact
- Feature Importance ranking charts derived directly from the Machine Learning model
- Departmental risk assessments

---

## 🔗 Project Link
https://github.com/rajeshpraharaj121/HR-Attrition-Analysis.git
