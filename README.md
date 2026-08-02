<!-- Header Banner with Animation -->
<div align="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=00c6ff&height=250&section=header&text=Customer%20Behavior%20Analysis&fontSize=45&animation=fadeIn&fontColor=ffffff" width="100%"/>
</div>

<!-- Animated Typing Text -->
<div align="center">
    <a href="https://readme-typing-svg.herokuapp.com"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00c6ff&center=true&vCenter=true&width=600&lines=Decoding+Customer+Behavior;Data-Driven+Business+Insights;Python+%7C+SQL+%7C+Power+BI" alt="Typing SVG" /></a>
</div>

---

## 📌 Overview
> **Transforming raw transactions into actionable business strategies.**

This project is a comprehensive **end-to-end data analytics initiative** focused on analyzing customer behavior patterns. It showcases the full analytics lifecycle — from raw data extraction and rigorous cleaning to advanced visualization and high-level presentation. The project demonstrates proficiency in uncovering trends that drive business growth and customer retention.

<br>

## 🛠️ Tools & Technologies

<div align="center">
  
  **Data Processing & Analysis**<br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pandas,numpy&theme=dark" alt="Python Pandas Numpy"/>
  </a>
  <br><br>
  
  **Database & Querying**<br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postgres,mysql&theme=dark" alt="SQL Databases"/>
  </a>
  <br><br>

  **Visualization & Presentation**<br>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Gamma-7F56D9?style=for-the-badge&logo=react&logoColor=white" alt="Gamma" />
  
</div>

---

## 📊 Dataset Overview

| 🏷️ Attribute | 📝 Description |
| :--- | :--- |
| **Source** | Customer transaction/purchase dataset |
| **Format** | `CSV` / `Excel` / Database export |
| **Key Fields** | `Customer ID`, `Purchase Date`, `Product Category`, `Quantity`, `Price`, `Total Spend`, `Payment Method`, `Location` |

---

## ⚙️ Analytics Pipeline & Workflow

```mermaid
graph TD;
    A[Raw Data] -->|Pandas| B(Data Loading & Inspection);
    B --> C(Exploratory Data Analysis - EDA);
    C -->|Handle Missing/Outliers| D(Data Cleaning);
    D -->|Export| E[(PostgreSQL / MySQL)];
    E -->|Complex Queries| F(SQL Analytical Insights);
    F -->|Data Modeling| G[Power BI Dashboard];
    G --> H(Gamma Presentation & Reporting);
    
    classDef default fill:#00c6ff,stroke:#000,stroke-width:1px,color:#fff;
    class E,G fill:#1e1e1e,stroke:#00c6ff,stroke-width:2px,color:#fff;

```

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|---------|
| Python | Data loading, cleaning, EDA |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Visualization during EDA |
| PostgreSQL / MySQL / SQL Server | Running analytical queries |
| Power BI | Interactive dashboard creation |


## 🔍 Steps Performed

### 1. Data Loading
- Loaded the dataset using Python's Pandas library
- Inspected data types, shape, and initial records

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Missing value detection
- Outlier analysis using boxplots & IQR method
- Univariate and bivariate analysis
- Correlation heatmaps to understand relationships

### 3. Data Cleaning
- Handled missing values using imputation/dropping
- Removed duplicates
- Standardized categorical values
- Formatted date/time columns

### 4. SQL Queries
- Exported cleaned data to PostgreSQL/MySQL/SQL Server
- Ran analytical queries for insights such as:
  - Top customers by total spend
  - Monthly purchase trends
  - Most popular product categories
  - Customer segmentation using grouping & aggregation

### 5. Power BI Dashboard
- Built interactive dashboards with:
  - Sales by category, region, and time
  - Customer loyalty segmentation
  - Key KPIs (Total Revenue, Avg Order Value, Active Customers)
  - Drill-through and filter capabilities

### 6. Report Generation
- Compiled findings into a structured business report
- Included charts, tables, and actionable recommendations

### 7. Presentation
- Created a clean, visually appealing slide deck using **Gamma**
- Summarized problem, process, insights, and business impact

## 📈 Key Insights (Sample)
- **Top 10%** of customers contribute to **~65%** of total revenue
- Weekend purchases are **30% higher** than weekday purchases
- Electronics and Fashion are the top-performing categories
- Majority of customers prefer **digital payment** methods

## 📊 Dashboard Preview
> *(Add screenshot of your Power BI dashboard here)*

## 🧾 How to Run This Project

### Prerequisites
- Python 3.x
- Jupyter Notebook / VS Code
- PostgreSQL / MySQL / SQL Server
- Power BI Desktop
- Gamma account (for PPT)

