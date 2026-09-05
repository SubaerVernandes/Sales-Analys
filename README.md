# Sales-Analys

# 📊 Regional Sales Analysis

> **End-to-End Data Analytics Project | Python • Pandas • Power BI • Business Intelligence**

An end-to-end **Regional Sales Analysis** project designed to transform five years of historical sales data into actionable business insights.

The project focuses on understanding **sales performance, profitability, customer behavior, product performance, sales channels, and regional trends** across the United States.

The analysis combines **Python-based Exploratory Data Analysis (EDA)** with an **interactive Power BI dashboard** to support data-driven sales and operational decisions.

---

## 🎯 Business Problem

The sales team lacks clear, data-driven visibility into regional performance, making it difficult to:

* Identify high-performing and underperforming regions
* Understand seasonal sales fluctuations
* Identify high-performing products and SKUs
* Evaluate sales channel contribution and profitability
* Understand customer revenue concentration
* Identify opportunities to improve profit margins
* Support strategic sales and resource allocation decisions

### Business Objective

The objective of this project is to analyze and visualize historical sales data to:

> **Identify growth opportunities, understand profitability drivers, and provide actionable recommendations for improving sales performance.**

---

# 🔎 Key Business Questions

This analysis addresses several important business questions:

1. Which regions and states generate the highest revenue?
2. How does sales performance change over time?
3. Which products contribute the most revenue?
4. Which products generate the highest profit margins?
5. Which sales channels contribute the most revenue?
6. Which customers generate the highest revenue?
7. Is revenue concentrated among a small number of customers?
8. What is the relationship between revenue, cost, price, quantity, and profit?
9. Which regions or customer segments require additional attention?
10. What strategic actions can improve revenue and profitability?

---

# 🛠️ Tools & Technologies

| Category              | Tools                           |
| --------------------- | ------------------------------- |
| Programming           | Python                          |
| Data Manipulation     | Pandas, NumPy                   |
| Data Visualization    | Matplotlib, Seaborn             |
| Data Analysis         | Exploratory Data Analysis (EDA) |
| Business Intelligence | Microsoft Power BI              |
| Data Preparation      | Power Query / Python            |
| Presentation          | PowerPoint                      |
| Environment           | Google Colab                    |

---

# 📂 Dataset Overview

The raw dataset contains sales-related information distributed across multiple tables, including:

* Sales
* Customers
* Products
* Regions
* States
* Channels
* Budget

The data was consolidated into a final analytical dataset containing:

### Customer & Order Information

* `order_number`
* `order_date`
* `customer_name`
* `channel`
* `product_name`

### Financial Metrics

* `quantity`
* `unit_price`
* `revenue`
* `cost`
* `profit`
* `profit_margin_pct`

### Calendar Features

* `order_month_name`
* `order_month_num`
* `order_month`

### Geographic Features

* `state`
* `state_name`
* `us_region`
* `lat`
* `lon`

### Planning

* `budget_2017`

---

# 🔄 Project Workflow

```text
Business Understanding
        ↓
Data Collection
        ↓
Data Consolidation
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Power BI Dashboard
        ↓
Business Recommendations
```

### 1. Business Understanding

Defined the core business problem and analytical objectives.

### 2. Data Collection & Consolidation

Combined sales, customer, product, geographic, regional, and budget information from multiple Excel sheets.

### 3. Data Cleaning

Performed:

* Column standardization
* Redundant column removal
* Header restructuring
* Data type formatting
* Table merging
* Key column selection
* Column renaming
* Data validation

The project documentation reports no missing values or duplicate rows after preprocessing.

### 4. Feature Engineering

Created additional analytical metrics including:

* `profit`
* `profit_margin_pct`
* `order_month`
* `order_month_num`
* `order_month_name`

### 5. Exploratory Data Analysis

Analyzed:

* Monthly sales trends
* Product performance
* Profit margins
* Sales channels
* State-level performance
* Regional performance
* Average Order Value (AOV)
* Customer revenue
* Customer segmentation
* Feature correlations

### 6. Dashboard Development

Built an interactive Power BI dashboard with multiple analytical views:

* **Performance Summary**
* **Customer Segmentation**
* **Revenue Scenario**

The dashboard enables users to explore sales performance interactively.

---

# 📈 Exploratory Data Analysis

## 1. Monthly Sales Trend

The analysis identified a relatively consistent sales cycle, with revenue generally ranging between **$24M–$26M**.

Key observations:

* May–June represent the seasonal peak.
* January represents an annual low point.
* Early 2017 showed a notable revenue decline.

This suggests that **seasonality should be incorporated into sales and inventory planning**.

---

## 2. Product Performance

Products **26 and 25** emerged as the leading revenue-generating products.

Meanwhile:

* Products 5, 13, 14, and 15 formed a middle-performing group.
* Products 1–4 were among the lowest revenue contributors.

### Business Implication

The business should:

* Protect availability of high-performing products.
* Identify growth opportunities for mid-tier products.
* Review pricing, cost structure, or demand drivers for low-performing SKUs.

---

## 3. Product Profitability

The highest-margin products consistently generated average margins above **$7.3K** in the analysis.

Top-performing products included:

* Product 18
* Product 28
* Product 5
* Product 11
* Product 12
* Product 26

This indicates that **revenue leadership and profitability leadership are not necessarily driven by the same products**, making both metrics important for portfolio decisions.

---

# 🌎 Regional & Geographic Analysis

## State-Level Performance

**California** emerged as the strongest state in terms of revenue and order volume.

Other significant states included:

* Texas
* Florida
* Illinois

The analysis indicates that revenue and order volume are strongly related at the state level.

---

## Regional Performance

The **West** region recorded the highest sales performance.

Regional observations:

| Region    | Performance                |
| --------- | -------------------------- |
| West      | Highest sales contribution |
| South     | Major sales contributor    |
| Midwest   | Stable / medium market     |
| Northeast | Lowest sales contribution  |

### Business Implication

The West provides a benchmark for understanding successful regional strategies, while the Northeast presents an opportunity for deeper market analysis and targeted growth initiatives.

---

# 🛒 Sales Channel Analysis

Revenue contribution by channel:

| Channel     | Revenue Contribution |
| ----------- | -------------------: |
| Wholesale   |            **54.1%** |
| Distributor |            **31.3%** |
| Export      |            **14.6%** |

Wholesale is the dominant sales channel.

However, the analysis also highlights **Export as an attractive channel from a profitability perspective**, creating an opportunity to balance revenue scale with margin performance.

---

# 👥 Customer Analysis

Customer analysis revealed significant revenue concentration.

**Aibox Company** emerged as the strongest revenue-generating customer, while the lowest-performing customers generated substantially less revenue.

This creates two strategic priorities:

### Customer Retention

Protect relationships with high-value customers that contribute disproportionately to total revenue.

### Customer Development

Identify opportunities to increase revenue from medium-value customers through:

* Upselling
* Cross-selling
* Targeted promotions
* Account-based strategies

---

# 💰 Customer Revenue vs. Profit Margin

Customer segmentation was performed using **revenue and profit margin**.

The analysis identified:

* Customers generating high revenue but relatively lower margins
* Customers with moderate revenue but strong margins
* Opportunities for targeted upselling
* Potential discount/pricing issues among large accounts

This allows the business to move beyond simply asking:

> **"Who generates the most revenue?"**

and instead ask:

> **"Which customers generate the most valuable revenue?"**

---

# 🔗 Correlation Analysis

The correlation analysis revealed several important relationships.

### Key Findings

* Unit price showed a very strong relationship with cost (**0.94**).
* Unit price also showed a strong relationship with revenue (**0.91**).
* Unit price had a strong relationship with profit (**0.79**).
* Revenue and profit showed a strong relationship (**0.87**).
* Quantity showed a relatively weaker relationship with financial metrics.

### Business Implication

The findings suggest that **pricing and cost management may provide stronger profitability levers than simply increasing sales volume**.

---

# 💡 Key Business Insights

### 1. Strong Seasonality

Sales performance follows a recognizable seasonal pattern, with May–June representing a strong period and January showing weaker performance.

### 2. Product Concentration

Products **26 and 25** account for approximately **25% of total sales**, creating both a growth opportunity and concentration risk.

### 3. Channel Concentration

Wholesale contributes approximately **54% of sales**, making it the primary revenue engine.

### 4. Geographic Concentration

California is the leading state, generating approximately **$230M in revenue and 7.6K orders**.

### 5. Customer Concentration

A small number of high-value customers contribute disproportionately to overall revenue.

### 6. Pricing Matters

The correlation analysis indicates that pricing is closely connected with cost, revenue, and profitability.

---

# 🚀 Business Recommendations

## 1. Seasonal Sales Strategy

Develop targeted campaigns during weaker periods while preparing inventory and resources ahead of seasonal peaks.

## 2. SKU Optimization

Increase focus on high-performing Products 26 and 25 while reviewing low-performing SKUs based on profitability and demand.

## 3. Channel Expansion

Maintain the scale of Wholesale while exploring additional growth through Export, particularly where higher margins can be achieved.

## 4. Regional Growth

Use California and the West region as benchmarks and investigate strategies that could improve performance in lower-performing regions.

## 5. Customer Value Management

Segment customers based on revenue and profitability to prioritize:

* Retention
* Upselling
* Cross-selling
* Pricing optimization

## 6. Margin Monitoring

Monitor low-margin accounts and investigate the underlying cost and pricing drivers.

---

# 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard consisting of three analytical pages:

### 01 — Performance Summary

Provides an overview of:

* Revenue
* Sales trends
* Product performance
* Channel performance
* Regional performance

### 02 — Customer Segmentation

Analyzes:

* Customer revenue
* Profitability
* Customer ranking
* Revenue vs. margin

### 03 — Revenue Scenario

Provides an interactive view for exploring revenue-related scenarios and business performance.

---

# 📸 Dashboard Preview

> Add your Power BI dashboard screenshots here.

Example:

```markdown
![Performance Summary](screenshots/dashboard-overview.png)

![Customer Segmentation](screenshots/customer-segmentation.png)

![Revenue Scenario](screenshots/revenue-scenario.png)
```

---

# 📁 Suggested Repository Structure

```text
Regional-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Regional_Sales_Analysis.ipynb
│
├── powerbi/
│   └── Regional_Sales_Analysis.pbix
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── customer-segmentation.png
│   └── revenue-scenario.png
│
└── presentation/
    └── Regional_Sales_Analysis.pptx
```

---

# 🎓 Skills Demonstrated

This project demonstrates practical capabilities in:

**Data Analytics**

* Exploratory Data Analysis
* Trend Analysis
* Customer Analysis
* Product Analysis
* Regional Analysis
* Profitability Analysis
* Correlation Analysis

**Data Preparation**

* Data Cleaning
* Data Transformation
* Data Integration
* Feature Engineering

**Business Intelligence**

* Dashboard Development
* KPI Analysis
* Interactive Data Visualization
* Business Storytelling

**Business Skills**

* Problem Solving
* Analytical Thinking
* Insight Generation
* Strategic Recommendations
* Data-Driven Decision Making

---

# 📌 Project Outcome

This project demonstrates an end-to-end analytical workflow:

> **Raw Data → Clean Data → EDA → Business Insights → Power BI Dashboard → Strategic Recommendations**

The final output transforms complex historical sales data into a business-oriented analytical solution that can support **sales planning, customer strategy, product optimization, regional expansion, and profitability management**.

---

# 👨‍💻 About Me

I am a **Mathematics graduate with a strong interest in Data Analytics and Data Science**, focused on transforming data into actionable business insights.

My analytical toolkit includes:

**Python | SQL | Excel | Power BI | Pandas | NumPy | Data Cleaning | EDA | Data Visualization**

I am particularly interested in opportunities where I can combine **analytical thinking, business understanding, and technical skills** to solve real-world problems using data.

---

## ⭐ Let's Connect

If you are a recruiter, hiring manager, or fellow data professional interested in discussing this project or potential opportunities, feel free to connect with me.

**Open to:**
`Data Analyst` • `Junior Data Analyst` • `Business Intelligence` • `Data Science`

---

## 📜 Disclaimer

This project is created for **portfolio and educational purposes**. The analysis focuses on demonstrating an end-to-end data analytics workflow, from data preparation and exploratory analysis to dashboard development and business recommendations.
