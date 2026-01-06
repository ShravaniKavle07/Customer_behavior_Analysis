Customer Shopping Behavior 

A  data analytics project on customer shopping behavior using Python, SOL and Power BI.


##  
**1. Overview**

This project analyzes **3,900 customer shopping transactions** to uncover insights about spending behavior, product trends, discount usage, and customer segments.

It demonstrates an **end-to-end analytics workflow**, including:

* Python-based data loading, cleaning, and EDA
* SQL queries on PostgreSQL / MySQL / SQL Server
* Power BI dashboard development
* Final business report creation
* Presentation built using **Gamma**

This project showcases technical skills, business analysis, and data storytelling.**
This project demonstrates a complete **end‑to‑end data analytics workflow**, starting from loading raw data in Python to generating insights through SQL queries, data visualization, dashboarding, and business reporting.

The project includes:

* Data loading & cleaning (Python)
* Exploratory Data Analysis (EDA)
* SQL‑based business queries (PostgreSQL / MySQL / SQL Server)
* Power BI interactive dashboard
* Final insights report
* Presentation created using **Gamma**

This project highlights strong analytical thinking, technical skills, and storytelling through data.


## 
**2. Dataset**

* **Rows:** 3,900
* **Columns:** 18
* **Data includes:**

  * Customer demographics (age, gender, location, subscription status)
  * Transaction information (item, category, purchase amount, size, color, season)
  * Behavioral attributes (discount applied, previous purchases, shipping type)
  * Review ratings (37 missing values → imputed)

The dataset required thorough cleaning and feature engineering before SQL and Power BI analysis.**

* Format: CSV
* Rows: Multiple thousand observations (dataset‑specific)
* Columns: Customer demographics, transactions, product details, and behavioral data
* Contains:

  * Numerical, categorical, and date fields
  * Some missing values
  * Requires cleaning and preprocessing

> *Note: You can replace this section with your actual dataset description if needed.*


## 
**3. Tools & Technologies Used**

### **Programming & Data Prep**

* Python (Pandas, NumPy, Matplotlib/Seaborn)

### **Database Systems**

* PostgreSQL
* MySQL
* SQL Server

### **Visualization & Reporting**

* Power BI (dashboard)
* Gamma (presentation)

### **Environment**

* Jupyter Notebook / VS Code
* Power BI Desktop
* SQL Workbench / pgAdmin / SSMS


## 
**4. Project Steps (Workflow)**

### **Step 1: Data Loading (Python)**

* Loaded CSV using Pandas and explored structure

### **Step 2: Data Cleaning & Feature Engineering**

* Imputed missing review ratings using category median
* Standardized all column names
* Created new fields: `age_group`, `purchase_frequency_days`, `customer_segment`
* Removed redundant `promo_code_used` column

### **Step 3: EDA (Python)**

* Visualized distributions, trends, and category behaviors
* Identified revenue drivers and spending patterns

### **Step 4: SQL Business Analysis**

Performed key SQL queries to understand:

* Revenue by gender and age group
* Top-rated / best-selling products
* Shipping impact on purchase amount
* Subscriber vs non-subscriber revenue
* Discount-dependent products
* Customer segmentation (New, Returning, Loyal)
* Likelihood of repeat buyers becoming subscribers

### **Step 5: Power BI Dashboard**

* Built interactive visuals for sales, customer segments, product analysis, and discount trends

### **Step 6: Final Report**

* Combined insights from Python + SQL + Power BI

### **Step 7: Gamma Presentation**

* Created a business-ready PPT summarizing insights and recommendations. (Workflow)**

### **Step 1: Load Data (Python)**

* Imported dataset using Pandas
* Inspected structure using `df.info()` and `df.describe()`

### **Step 2: Data Cleaning**

* Handled missing values
* Removed duplicates
* Standardized column names
* Converted data types (dates, numeric fields)
* Created new derived columns for deeper insight

### **Step 3: Exploratory Data Analysis**

* Univariate, bivariate, and multivariate analysis
* Data visualization (bar plots, heatmaps, distributions)
* Identified trends, patterns, and anomalies

### **Step 4: SQL Business Analysis**

Executed SQL queries to answer key business questions:

* Revenue analysis
* Customer segmentation
* Product performance
* Discount & shipping patterns
* High‑value customer identification

### **Step 5: Power BI Dashboard**

* Imported cleaned dataset
* Built interactive charts & slicers
* Created pages for sales, customers, products, and performance KPIs

### **Step 6: Final Report**

* Summarized insights from Python + SQL + Power BI
* Included visualizations and business recommendations

### **Step 7: Gamma Presentation**

* Created a polished PPT using AI‑powered Gamma
* Focused on story, visuals, and business impact


## 
**5. Power BI Dashboard**

Dashboard includes:

* Key metrics (Total Revenue, Avg Order Value, Customers)
* Revenue by Age Group, Gender, Region
* Top 5 products by rating and sales
* Shipping comparison: Standard vs Express
* Discount trends and subscription insights

Interactive slicers allow deeper exploration across categories & seasons.**
Dashboard includes:

* Overall KPIs (Revenue, Orders, Customers)
* Sales by category, product, region
* Customer demographics and segments
* Time‑series revenue trends
* Discount & subscription behavior

The dashboard enables interactive filtering and exploration.

## 
**6. Results & Key Findings**

Key insights derived:

* **25–34 & 35–44** age groups generate the highest revenue
* **Subscribers** spend more and return more frequently
* **Express shipping users** show higher purchase amounts
* Identified top-rated and most purchased products for marketing focus
* **Discount-dependent products** require review for profitability
* Customers with **>5 purchases are more likely to subscribe**

These insights inform customer strategy, pricing, and marketing decisions.**
This project delivers:

* Clean dataset ready for modeling or analysis
* Insightful visual patterns from EDA
* SQL‑based answers to real business questions
* Interactive BI dashboard for decision‑making


## 
**7. How to Run the Project**

### **Prerequisites**

* Python 3.x
* PostgreSQL/MySQL/SQL Server installed (any one)
* Power BI Desktop
* Required Python libraries:

  ```
  pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2 pymysql pyodbc
  ```


## 
**Contact**

For collaboration:

* **Name:** Shravani Kavle
* **Email:** shravanikavle369@gmail.com
* **LinkedIn:** https://www.linkedin.com/in/shravanikavle07/
