# 📊 Healthcare Analytics Dashboard
A comprehensive and interactive Power BI dashboard designed to provide a healthcare center with actionable insights into its financial performance and healthcare provider efficiency. This project transforms raw operational data into strategic intelligence, enabling data-driven decision-making.

### ❓ Problem Statement
Healthcare organizations frequently struggle with consolidating disparate operational and financial data to gain a holistic view of performance. Challenges include understanding revenue streams, managing costs, assessing provider efficiency, and identifying critical trends, often leading to reactive strategic planning due to a lack of readily available, insightful visualizations.

### ✅ Solution
This project delivers a multi-page Power BI dashboard that enables stakeholders to:

Analyze Financial Health: Summarize total revenue, costs, and net income.

Evaluate Provider Performance: Assess individual provider efficiency and patient satisfaction.

Identify Key Trends: Highlight financial and operational patterns over time.

Explore Deeper Insights: Understand patient demographics, common diagnoses, and procedures.

The solution leverages advanced DAX, robust data modeling, and interactive visuals to mimic real-world business intelligence scenarios.

### 📂 Dataset Overview
The dashboard integrates data from eight distinct CSV files, forming a comprehensive healthcare dataset:

visits.csv: Core fact table detailing patient visits, costs, dates, and satisfaction.

patients.csv: Patient demographics (ID, Name, Gender, Age, City ID, Race).

providers.csv: Healthcare provider details (ID, Name, Gender, Nationality, Age, Image).

departments.csv: Healthcare department information (ID, Name).

diagnoses.csv: Medical diagnosis codes and descriptions (ID, Name).

procedures.csv: Medical procedure codes and descriptions (ID, Name).

insurance.csv: Insurance provider details (ID, Name).

cities.csv: City details for patient locations (ID, City, State).

### 🧠 Key Features
## 📌 Page 1: Executive Financial Overview
KPIs: Total Revenue, Total Treatment Cost, Total Medication Cost, Total Room Charges, Total Insurance Coverage, Net Revenue.

Visuals:

Line chart for Total Revenue Trend over time.

Bar chart for Revenue by Service Type (Inpatient, Outpatient, Emergency).

Donut chart for Payment Status Distribution (Paid, Pending, Denied).

### 📌 Page 2: Provider Performance Insights
KPIs: Total Visits per Provider, Average Patient Satisfaction Score, Average Revenue per Visit, Total Treatment Cost per Provider.

Visuals:

Table/Matrix for detailed provider metrics.

Bar chart for Total Visits per Provider.

Scatter plot comparing Average Patient Satisfaction vs. Average Treatment Cost per provider.

Calculated Column: Primary Department (in providers table) based on department with most visits.

### 📌 Page 3: Detailed Trend Analysis
Visuals:

Line chart for Total Revenue Trend (with drill-down hierarchy).

Line chart for Total Visits Trend (with drill-down hierarchy).

Combo chart showing Total Revenue and Total Revenue YoY Growth %.

Stacked Area chart for Revenue by Service Type Trend over time.

### 📌 Page 4: Additional Insights
Visuals:

Bar chart for Top Diagnoses by Total Treatment Cost.

Bar chart for Top Procedures by Total Treatment Cost.

Donut chart for Patient Distribution by Race.

Treemap for Patient Distribution by Age Group.

Calculated Column: Age Group (in patients table) for demographic segmentation.

# ⚙️ Tools & Techniques
Power BI Desktop : Report creation, visual design, and data modeling.

Power Query (M) : Data cleaning, transformation (e.g., date format consistency, handling null values, converting cost fields to numeric).

DAX: Advanced KPIs, measures (e.g., Total Room Charges, Total Revenue, Net Revenue), time intelligence (YoY, YTD), and custom calculated columns (Duration of Stay (Days), Primary Department, Age Group).

Relationships: Establishing a robust star schema across 8 tables for seamless cross-filtering.

Slicers: Dynamic filtering by Date, City, Provider, Department, Diagnosis, Procedure, Race, Age Group.

Visualizations: Diverse chart types (Cards, Line, Bar, Donut, Scatter, Treemap) for effective data communication.

Data Quality: Implementing DAX logic to handle data quality issues like negative durations in stay.

# 🎯 Business Impact
With this solution, healthcare executives and operational managers can:

Optimize Financial Performance: Gain clear visibility into revenue streams, cost drivers, and payment statuses to enhance financial planning.

Improve Provider Efficiency: Identify top-performing providers, assess patient satisfaction, and understand cost implications per provider.

Proactive Planning: Spot emerging trends in visits, revenue, and service types to inform strategic decisions.

Enhance Patient Care: Understand demographic patterns and the impact of specific diagnoses/procedures on costs and patient experience.

Data-Driven Decisions: Transition from reactive to proactive management through consolidated, interactive, and insightful data visualizations.

# 📝 How to Use
Download or clone this repository.

Open the .pbix file in Power BI Desktop.

Explore the interactive visuals using the various slicers (department, provider, date, city, etc.).

Adapt the dashboard for your specific analytical needs or academic use.

# 👨‍💻 Author
Abhrajit Das | Data Analyst & Power BI Developer
