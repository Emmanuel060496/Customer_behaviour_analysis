# Customer_behaviour_analysis
data analytics project showcasing customer behavior analysis using python, sql and power Bi.
# Customer Shopping Behaviour Analysis

## Overview

This project presents an end-to-end data analytics solution designed to analyse customer shopping behaviour and purchasing patterns. The aim was to identify key trends, customer preferences, purchasing habits, and factors influencing spending behaviour through data analysis, SQL querying, and interactive visualisation.

The project covers the complete analytics lifecycle, including data preparation, exploratory analysis, database querying, dashboard development, reporting, and presentation of findings.

---

## Dataset

**Dataset Name:** Customer Shopping Behaviour Dataset

**Source:** Public Retail Customer Shopping Dataset

**Description:**

The dataset contains customer shopping transaction information, demographic details, purchasing behaviour, and customer preferences.

Key attributes include:

* Customer ID
* Age
* Gender
* Item Purchased
* Product Category
* Purchase Amount (USD)
* Location
* Size
* Colour
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

**Dataset Size:**

* Records: 3,900
* Features: 18

---

## Project Objectives

The objectives of this project were to:

* Analyse customer purchasing behaviour.
* Identify spending patterns across customer segments.
* Examine the impact of discounts and promotional campaigns.
* Explore customer preferences by category, season, and location.
* Understand relationships between demographics and spending.
* Develop an interactive dashboard for business stakeholders.
* Generate actionable recommendations to improve customer engagement and sales performance.

---

## Tools and Technologies

| Tool                            | Purpose                                |
| ------------------------------- | -------------------------------------- |
| Python                          | Data analysis and preprocessing        |
| Pandas                          | Data manipulation                      |
| NumPy                           | Numerical analysis                     |
| Matplotlib                      | Data visualisation                     |
| Seaborn                         | Exploratory Data Analysis              |
| SQL                             | Data querying and business analysis    |
| PostgreSQL / MySQL / SQL Server | Database management                    |
| Power BI                        | Dashboard development                  |
| Gamma                           | Presentation creation                  |
| Jupyter Notebook                | Analysis environment                   |
| GitHub                          | Version control and portfolio showcase |

---

## Project Workflow

### 1. Data Loading

The dataset was imported into Python using Pandas and examined to understand:

* Data structure
* Data types
* Missing values
* Summary statistics

---

### 2. Exploratory Data Analysis (EDA)

EDA was conducted to uncover patterns and trends within the data.

Key analyses included:

* Customer age distribution
* Gender analysis
* Product category popularity
* Spending patterns by category
* Seasonal purchasing trends
* Customer review ratings
* Geographic distribution of purchases
* Purchase frequency analysis
* Payment method preferences

Visualisations were created using Matplotlib and Seaborn to support findings.

---

### 3. Data Cleaning

The following data quality checks were performed:

* Checked for missing values
* Reviewed data consistency
* Validated numerical fields
* Standardised categorical values
* Prepared data for SQL and Power BI analysis

---

### 4. SQL Analysis

The cleaned dataset was loaded into PostgreSQL, MySQL, or SQL Server for further analysis.

Example business questions answered:

* Which product categories generate the highest sales?
* Which age groups spend the most?
* Which states have the highest purchase volumes?
* What payment methods are most frequently used?
* How do discounts influence purchase amounts?
* Which customer segments make repeat purchases?

Example SQL operations:

* SELECT statements
* Filtering and sorting
* GROUP BY aggregations
* Window functions
* Ranking queries
* Business KPI calculations

---

### 5. Power BI Dashboard

An interactive dashboard was developed to provide stakeholders with real-time insights into customer shopping behaviour.

Dashboard pages included:

#### Executive Summary

* Total Customers
* Total Revenue
* Average Purchase Amount
* Average Review Rating

#### Customer Insights

* Age Group Analysis
* Gender Distribution
* Subscription Status

#### Sales Performance

* Revenue by Category
* Revenue by Season
* Revenue by Location

#### Customer Behaviour

* Purchase Frequency
* Payment Method Analysis
* Discount and Promotion Analysis

---

## Dashboard

### Key KPIs

* Total Customers
* Total Sales Revenue
* Average Purchase Value
* Average Customer Rating
* Repeat Purchase Rate
* Subscription Adoption Rate

### Interactive Features

* Category Filters
* Location Filters
* Season Filters
* Customer Demographic Filters
* Drill-through Analysis
* Dynamic KPI Cards

---

## Key Findings

### Customer Insights

* Clothing products generated the highest volume of purchases.
* Most customers were aged between 30 and 60 years.
* Subscription status influenced purchasing frequency.
* Certain payment methods were preferred over others.
* Seasonal trends impacted purchasing behaviour across product categories.

### Business Recommendations

* Increase targeted promotions for high-value customer segments.
* Focus marketing efforts on top-performing categories.
* Encourage subscription adoption through loyalty incentives.
* Optimise seasonal campaigns based on purchasing trends.
* Improve customer retention through personalised offers.

---

## Project Structure

```text
customer-shopping-analysis/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── cleaned_customer_data.csv
│
├── notebooks/
│   └── customer_shopping_eda.ipynb
│
├── sql/
│   └── customer_analysis_queries.sql
│
├── dashboard/
│   └── customer_shopping_dashboard.pbix
│
├── reports/
│   └── customer_shopping_report.pdf
│
├── presentation/
│   └── gamma_presentation.pdf
│
├── images/
│   └── dashboard_screenshots/
│
├── README.md
│
└── requirements.txt
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/customer-shopping-analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd customer-shopping-analysis
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

### 4. Run the Analysis

```bash
jupyter notebook
```

Open:

```text
notebooks/customer_shopping_eda.ipynb
```

and run all cells.

### 5. Execute SQL Queries

Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server and execute the scripts located in:

```text
sql/customer_analysis_queries.sql
```

### 6. Open Power BI Dashboard

Open:

```text
dashboard/customer_shopping_dashboard.pbix
```

to explore the interactive dashboard.

---

## Deliverables

* Customer Shopping Dataset
* Python EDA Notebook
* Data Cleaning Scripts
* SQL Analysis Queries
* Power BI Dashboard
* Business Report
* Gamma Presentation
* Project Documentation

---

## Business Value

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* SQL Analytics
* Business Intelligence
* Dashboard Development
* Data Storytelling
* Stakeholder Reporting

It showcases the complete workflow expected of a Data Analyst and Business Intelligence professional.

---

## Contact
* Email: ajilore33@gmail.com
* LinkedIn: https://www.linkedin.com/in/emmanuel-ajilore-424442220/
