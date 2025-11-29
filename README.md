# HR Analytics Dashboard — Power BI Project

**HR Analytics Dashboard** is a Power BI project designed to analyze HR data for a company of 1,470 employees. The dashboard helps HR teams monitor workforce composition, track key HR KPIs, explore attrition patterns, and generate actionable insights for decision making.

---

## 📌 Project Goals
- Provide a clear picture of workforce composition (by department, age, gender, education).
- Track core HR KPIs: Total Employees, Active Employees, Attrition, Attrition Rate, Average Salary, Average Age.
- Identify high-risk groups for employee turnover.
- Deliver interactive visuals to support HR decision-making (C&B, retention, workforce planning).

---

## 📁 Data Overview
The dataset contains 1,470 employee records with fields such as:
- **Demographics:** Age, Gender, Education  
- **Employment:** Department, Job Role, Years At Company  
- **Finance:** Monthly Income  
- **Performance:** Performance Rating, Job Satisfaction  
- **Attrition:** Yes / No  

Data was cleaned, standardized, and modeled before visualization.

---

## 🛠️ Project Structure
The Power BI report includes **three pages**:

### **1️⃣ Overview Analysis**
- Total Employee, Attrition, Attrition Rate, Active Employee  
- Average Salary, Average Age  
- Workforce distribution by Department, Gender × Age Band, Education, and Job Satisfaction  
- Average Salary by Job Role  

### **2️⃣ Attrition Analysis**
- Attrition Rate by Department, Job Role, Age Band, Education, Gender  
- Attrition by Years at Company (Tenure patterns)  
- Identification of high-turnover groups  

### **3️⃣ Employee Details**
- Employee-level table with fields: ID, Gender, Department, Job Role, Age, Income, Attrition, Performance Rating  
- Interactive slicers: Department & Job Role  

---

## 📐 Data Modeling & DAX
- Cleaned data using **Power Query**
- Built a simplified **star-schema model**
- Key DAX measures:
  - `Total Employees`
  - `Active Employees`
  - `Attrition Count`
  - `Attrition Rate = DIVIDE([Attrition Count], [Total Employees])`
  - `Average Salary`
  - `Average Age`

---

## 📊 Insights
- **Attrition Rate (overall):** 16.12%  
- **Highest attrition age group:** Under 25 → *39.18%*  
- **High-turnover roles:** Sales Representative (≈39.76%), Laboratory Technician (≈23.94%)  
- **Tenure effect:** Employees with 1–3 years experience have the highest turnover  
- **Gender:** Male attrition is slightly higher than Female  
- **Education:** Not a strong predictor of attrition  

These insights suggest retention challenges among junior employees and certain frontline roles.



