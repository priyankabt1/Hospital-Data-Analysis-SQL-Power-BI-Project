# 🏥 Hospital Performance Dashboard

## 📘 Overview
This project analyzes **Hospital Performance Metrics** using **SQL** for data analysis and **Power BI** for visualization.  
The goal is to track key performance indicators (KPIs) such as **Bed Utilization**, **Patient Satisfaction**, **Admissions Trend**, and **Refusal Rate**, helping hospital management make data-driven decisions.

---


---

### Objective
To clean, aggregate, and prepare hospital data for Power BI visualization.

### Key Analytical Queries (Concepts Only)
1. **Total Patients**  
   - Counts the number of admitted patients.
   - Basis for trend and service-wise analysis.

2. **Bed Utilization Rate**  
   - Calculates average percentage of occupied beds.

3. **Average Patient Satisfaction**  
   - Aggregates satisfaction scores by service and age group.

4. **Admissions Trend Analysis**  
   - Monthly admissions to track changes in patient volume.

5. **Refusal Rate by Service**  
   - Measures patients refused admission compared to total requests.

6. **Capacity vs Demand Analysis**  
   - Compares available capacity to actual patient demand.

Each query output was loaded into Power BI as a dataset for visualization.

---

## 📊 Power BI Dashboard

### Dashboard Name
**Hospital Performance Overview**

### Key Visuals

| Visualization | Description |
|----------------|--------------|
| **KPIs** | Displays key metrics: Bed Utilization %, Total Patients, Avg. Satisfaction, Total Requests |
| **Donut Chart** | Average satisfaction segmented by age group |
| **Bar Chart** | Demand vs Capacity across services |
| **Combo Chart** | Avg. Satisfaction and Bed Utilization % by Service |
| **Line Chart** | Admissions Trend over time |
| **Scatter Chart** | Refusal Rate % vs Staff Morale by Service |
| **Table** | Month-wise performance breakdown with service filters |

---

## ⚙️ Steps to Recreate

### Step 1: Database Setup
- Import hospital data into your preferred SQL database (e.g., MySQL, PostgreSQL, SQL Server).
- Run the SQL scripts in the `/SQL_Queries/` folder to clean and transform data.

### Step 2: Load Data into Power BI
- Connect Power BI to your SQL database or export query outputs as `.csv` files.
- Load them into Power BI using **Get Data → SQL Server / CSV**.

### Step 3: Build Visualizations
- Create KPIs using **cards**.
- Build bar, line, donut, and scatter visuals using prepared tables.
- Add **filters** for `Service` and `Month` slicers for interactivity.

### Step 4: DAX Calculations
- Define key measures such as:
  - Bed Utilization %
  - Average Satisfaction
  - Refusal Rate %
- Apply these measures to visuals.

### Step 5: Dashboard Formatting
- Apply consistent color theme.
- Add title: **"Hospital Performance Overview"**.
- Arrange visuals neatly on one page for clarity.

---

## 🧠 Insights Derived
- **Bed Utilization Rate** maintained around 92%.
- **Emergency Department** had highest patient load and refusal rate.
- **Older age groups** reported slightly lower satisfaction levels.
- **Seasonal trend** visible in monthly admissions.
- **ICU performance** was stable but limited by capacity constraints.

---

## 🧾 Tools Used
- **SQL** (MySQL / PostgreSQL)
- **Power BI Desktop**
- **Excel / CSV** (for data import)
- **GitHub** (for version control)


## 👨‍💻 Author
**Priyanka**
Data Analyst
