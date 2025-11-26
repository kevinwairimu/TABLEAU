# 👥 HR Attrition Analysis Dashboard

This Tableau dashboard analyzes employee attrition patterns using cleaned Excel data. It highlights key HR metrics, demographic trends, and satisfaction insights to help stakeholders understand turnover drivers and workforce dynamics.

---

## 📸 Dashboard Preview

![HR Attrition Dashboard Screenshot](Dashboard_Screenshot.png)  
*Visual overview of attrition KPIs, department trends, age distribution, job satisfaction, and gender-based analysis.*

---

## 📊 Dashboard Highlights

- **Key Performance Indicators (KPIs)**  
  - Total Employees (from Employee Number)  
  - Attrition Count (calculated field)  
  - Attrition Rate = Attrition Count / Total Employees (formatted as percentage)  
  - Active Employees = Total Employees − Attrition Count  
  - Average Age

- **Education Filter**  
  Enables dynamic filtering across all visualizations based on employee education level.

- **Attrition by Gender**  
  Lollipop chart using dual axis: Gender on rows, Attrition Count on columns.

- **Attrition by Department**  
  Pie chart showing attrition distribution across departments (Sales, R&D, HR).

- **Employee Age Distribution**  
  Frequency chart using age bins (increment of 1) to show employee count per age.

- **Job Satisfaction Heatmap**  
  Heatmap showing satisfaction ratings (1–4) across job roles and departments.

- **Education-wise Attrition**  
  Bar chart comparing attrition counts across education fields (Life Sciences, Technical Degree, Medical, etc.).

---

## ⚙️ Techniques Used

- Excel data cleaning and preparation  
- Calculated fields for attrition metrics  
- Parameter-driven bin sizing for age distribution  
- Dual-axis lollipop chart for gender analysis  
- Heatmap formatting for satisfaction scores  
- Interactive filters and tooltips for HR storytelling

---

## 📁 Folder Structure

- `Dashboards/HR Attrition Analysis/`  
  └── `HR_Attrition_Analysis.twbx`  
  └── `Dashboard_Screenshot.png`  
  └── `README.md` ← *this file*

---

## 🔍 How to View

1. Open `HR_Attrition_Analysis.twbx` in Tableau Desktop or Tableau Public.  
2. Use the education filter to explore attrition patterns across demographics.  
3. Refer to the screenshot for a quick visual overview.

---

💡 *This project demonstrates  ability to use Tableau for HR analytics, KPI logic, and demographic storytelling through interactive dashboards.*