# Elevate-labs-Projects
Project 1 = HR Analytics - Predict Employee Attrition
💼 HR Analytics – Employee Attrition Dashboard
This project focuses on analyzing employee attrition using HR data to identify which roles, departments, or conditions (like overtime) are most prone to resignation. The outcome is a professional and interactive dashboard built in Power BI.

📊 Project Objective
To understand the main causes behind employee resignations and empower HR teams to make data-driven decisions for improving employee retention and engagement.

🛠 Tools Used

Tool	Purpose
Power BI	Data cleaning, visualization, dashboard
Excel	Basic data preview (optional)
📁 Dataset
Source: IBM HR Employee Attrition Dataset

Records: 1470 employees

Key Columns: Attrition, Department, JobRole, OverTime, Gender, MonthlyIncome, YearsAtCompany, etc.

🧱 Project Steps
Imported dataset into Power BI

Cleaned and transformed data in Power Query Editor

Created calculated fields (e.g., Age Group, Attrition %)

Designed KPI cards:

Total Employees

Employees Left

Attrition Rate (%)

Created visuals:

Attrition by Job Role (Bar Chart)

Attrition by Department (Bar Chart)

Attrition by OverTime (Column Chart)

Attrition by Years at Company (Line Chart)

Added Slicers:

Gender, Department, Job Role, OverTime

Designed with custom green-black theme

Exported screenshot and report

🔍 Key Insights
Sales Executives and R&D employees had the highest attrition

Employees working overtime were more likely to leave

Most resignations occurred between 5–10 years of service

📦 Deliverables
📊 HR_Attrition_Dashboard.pbix – https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/HR%20Employee%20Analysis.pbix

📸 HR_Attrition_Dashboard_Screenshot.png – https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/HR%20Employee%20Analysis.png

📄 HR_Employee_Attrition_Report.pdf – https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/HR%20Employee%20Analysis%20Report.docx

📂 Dataset: https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/HR-Employee-Attrition-Analysis.csv.csv



Project 2 =  E-commerce Return Rate Reduction Analysis

#  E-commerce Return Rate Reduction Analysis

This project analyzes e-commerce product returns to uncover the underlying patterns and causes. The goal is to identify trends across categories, locations, and return reasons in order to reduce return rates and improve customer satisfaction.

## 📌 Project Objectives

- Understand why customers return products.
- Identify categories and locations with high return rates.
- Recommend data-driven strategies to reduce returns.

## 📁 Dataset

- Name: `ecommerce_returns_synthetic_data.csv`
- Records contain:
  - `order_id`, `order_date`, `product_category`, `customer_segment`, `customer_location`, `return_reason`
- Additional engineered fields:
  - `return_flag`: Binary flag (1 = Returned, 0 = Not Returned)
  - `Order_Month`: Month-Year derived from order_date

## 🧹 Data Cleaning & Preparation

- Missing values in `return_reason` were replaced with "Not Returned".
- `return_flag` field added to distinguish returns.
- Order month extracted for time series analysis.

## 📊 Power BI Dashboard

The interactive dashboard includes:

- KPI Cards:
  - Total Orders
  - Total Returns
  - Return Rate (%)

- Visualizations:
  - Bar chart of returns by product category
  - Pie chart of return reasons
  - Line chart showing return trend by month
  - Map showing geographic return distribution
  - Optional: Stacked chart by customer segment

## 🔍 Key Insights

- Specific categories and locations have higher return rates.
- Top return reasons include: defective items, wrong product, and quality dissatisfaction.
- Return volumes exhibit monthly and seasonal trends.

## ✅ Recommendations

- Address product quality in high-return categories.
- Optimize packaging and order fulfillment.
- Provide clearer product descriptions and sizing guides.
- Modify return policies for high-return geographies.

## 📦 Deliverables

- 📊 Power BI Dashboard (`.pbix`) - https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/E-commerce%20Return%20Rate%20Reduction%20Analysis.pbix
- 📄 Project Report (PDF/Word) - https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/E-commerce%20Return%20Rate%20Reduction%20Analysis%20Report.docx
- 📁 Dataset (CSV) - https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/ecommerce_returns_synthetic_data.csv
- 🖼 Dashboard Screenshots - https://github.com/Sanchitashejwal/Elevate-labs-Projects/blob/main/E-commerce%20Return%20Rate%20Reduction%20Analysis.png

## 📌 Conclusion

This project identifies actionable insights to reduce returns, improve logistics, and elevate customer experience in e-commerce platforms.
