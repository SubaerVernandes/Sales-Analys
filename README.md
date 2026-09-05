# 📊 Regional Sales Analysis

### Turning Sales Data into Actionable Business Insights

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Analysis-orange?style=for-the-badge" />
</p>

<p align="center">
  <b>End-to-End Data Analytics Project</b><br>
  Python • Pandas • NumPy • Matplotlib • Seaborn • Power BI
</p>

---

## 📌 Executive Summary

**Regional Sales Analysis** is an end-to-end data analytics project focused on transforming **five years of historical sales data** into actionable business insights.

The project analyzes sales performance across multiple dimensions:

* 🌎 **Region & State**
* 📦 **Product & SKU**
* 🛒 **Sales Channel**
* 👥 **Customer**
* 📅 **Time & Seasonality**
* 💰 **Revenue & Profitability**

The analytical process starts with **data consolidation and preprocessing**, continues through **Exploratory Data Analysis (EDA)**, and ends with an **interactive Power BI dashboard and strategic business recommendations**.

> **Goal:** Identify growth opportunities, understand profitability drivers, and provide data-driven recommendations for sales and operational decisions.

---

# 🎯 Business Problem

The sales team has limited visibility into regional and commercial performance, making it difficult to identify:

* High- and low-performing regions
* Seasonal fluctuations in revenue
* High-performing products and SKUs
* Sales channel contribution
* Customer revenue concentration
* Profitability drivers
* Opportunities for revenue and margin improvement

### Business Objective

Develop a data-driven analytical solution that can answer:

> **What is driving sales performance, where are the biggest opportunities, and what actions should the business prioritize?**

---

# 🔍 Business Questions

The analysis was designed around the following questions:

| #  | Business Question                                           |
| -- | ----------------------------------------------------------- |
| 01 | Which states and regions generate the highest revenue?      |
| 02 | How does revenue change over time?                          |
| 03 | Are there significant seasonal patterns?                    |
| 04 | Which products contribute the most revenue?                 |
| 05 | Which products generate the strongest margins?              |
| 06 | Which sales channels contribute the most revenue?           |
| 07 | Which customers generate the highest revenue?               |
| 08 | Is revenue concentrated among a small number of customers?  |
| 09 | What factors are most strongly associated with profit?      |
| 10 | What strategic actions can improve sales and profitability? |

---

# 🧠 Analytical Approach

The project follows a structured **end-to-end analytics lifecycle**:

```text
                 BUSINESS PROBLEM
                       │
                       ▼
               DATA COLLECTION
                       │
                       ▼
            DATA CONSOLIDATION
                       │
                       ▼
          DATA CLEANING & PREPARATION
                       │
                       ▼
             FEATURE ENGINEERING
                       │
                       ▼
           EXPLORATORY DATA ANALYSIS
                       │
                       ▼
               BUSINESS INSIGHTS
                       │
                       ▼
             POWER BI DASHBOARD
                       │
                       ▼
          BUSINESS RECOMMENDATIONS
```

This workflow ensures that the final dashboard is not just a visualization layer, but the output of a structured analytical process.

---

# 🛠️ Tech Stack

### Programming & Analysis

| Technology    | Purpose                       |
| ------------- | ----------------------------- |
| 🐍 Python     | Data analysis & preprocessing |
| 🐼 Pandas     | Data manipulation             |
| 🔢 NumPy      | Numerical computation         |
| 📊 Matplotlib | Data visualization            |
| 📈 Seaborn    | Statistical visualization     |

### Business Intelligence

| Technology          | Purpose                           |
| ------------------- | --------------------------------- |
| 🟨 Power BI         | Interactive dashboard             |
| 🔄 Power Query      | Data transformation               |
| 📊 Power BI Visuals | Business reporting & storytelling |

### Supporting Tools

```text
Google Colab
Microsoft Excel
PowerPoint
GitHub
```

---

# 📂 Dataset Structure

The raw data was distributed across multiple tables covering:

```text
Sales
├── Orders
├── Customers
├── Products
├── States
├── Regions
├── Channels
└── Budget
```

The final analytical dataset was structured around several analytical dimensions.

### Order & Customer

```text
order_number
order_date
customer_name
channel
product_name
```

### Financial

```text
quantity
unit_price
revenue
cost
profit
profit_margin_pct
```

### Time

```text
order_month
order_month_num
order_month_name
```

### Geography

```text
state
state_name
us_region
lat
lon
```

### Planning

```text
budget_2017
```

---

# 🧹 Data Preparation

The preprocessing stage focused on creating a reliable analytical dataset.

### Key activities

* Header restructuring
* Data consolidation
* Table merging
* Redundant column removal
* Column standardization
* Column renaming
* Data type formatting
* Key field selection
* Data validation

### Feature Engineering

Two important business metrics were created:

```text
Profit
Profit Margin %
```

Additional calendar features were also created to support time-series analysis.

The project documentation reports that **no missing values or duplicate rows were found after preprocessing**.

---

# 📊 Exploratory Data Analysis

The EDA phase focused on understanding:

```text
WHAT  → What is happening?
WHERE → Where is it happening?
WHY   → What could be driving it?
```

The analysis covered:

* Sales trends
* Product performance
* Profitability
* Sales channels
* Geographic performance
* Customer concentration
* AOV distribution
* Customer segmentation
* Feature correlations

---

# 📈 Key Findings

## 01 — Strong Seasonal Pattern

Monthly sales showed a relatively consistent cycle.

### Key observation

* **May–June:** seasonal peak
* **January:** annual low point
* **Early 2017:** significant revenue decline

This suggests that sales and operational planning should account for recurring seasonal behavior.

---

## 02 — Product Concentration

Products **26 and 25** emerged as the strongest revenue contributors.

Together, they represented approximately:

> **~25% of total sales**

This creates both:

**Opportunity** → prioritize high-performing products

**Risk** → excessive dependence on a limited number of SKUs

---

## 03 — Wholesale Is the Primary Revenue Engine

Revenue contribution by channel:

| Channel        | Contribution |
| -------------- | -----------: |
| 🥇 Wholesale   |    **54.1%** |
| 🥈 Distributor |    **31.3%** |
| 🥉 Export      |    **14.6%** |

Wholesale represents the largest revenue contributor, while Export presents an opportunity to explore higher-margin growth.

---

## 04 — California Leads the Market

California emerged as the strongest state in both revenue and order volume.

### Performance

```text
Revenue     ≈ $230M
Orders      ≈ 7.6K
```

Other significant states included:

* Texas
* Florida
* Illinois

---

## 05 — West Region Leads Sales

Regional performance showed:

| Region     | Performance       |
| ---------- | ----------------- |
| 🥇 West    | Highest           |
| 🥈 South   | Major contributor |
| 🥉 Midwest | Stable            |
| Northeast  | Lowest            |

The **West** region demonstrated strong market performance, while the Northeast represents an opportunity for deeper market investigation.

---

## 06 — Revenue Concentration Among Customers

Customer analysis revealed a substantial difference between the highest- and lowest-performing customers.

**Aibox Company** emerged as the leading revenue-generating customer.

This indicates the importance of:

* Customer retention
* Key-account management
* Upselling
* Cross-selling
* Revenue diversification

---

## 07 — Pricing Is a Major Profitability Driver

Correlation analysis revealed strong relationships between unit price and financial performance.

| Relationship         | Correlation |
| -------------------- | ----------: |
| Unit Price ↔ Cost    |    **0.94** |
| Unit Price ↔ Revenue |    **0.91** |
| Revenue ↔ Profit     |    **0.87** |
| Unit Price ↔ Profit  |    **0.79** |
| Cost ↔ Profit        |    **0.58** |

Quantity showed comparatively weaker relationships with financial metrics.

### Business Interpretation

The findings suggest that **pricing and cost management may provide stronger profitability levers than simply increasing sales volume**.

---

# 💡 Strategic Insights

The analysis can be summarized into five major themes:

```text
SEASONALITY
    ↓
Plan inventory & campaigns around demand cycles

PRODUCT
    ↓
Protect high-performing SKUs & optimize weak performers

CHANNEL
    ↓
Maintain Wholesale scale while developing Export

REGION
    ↓
Replicate successful regional strategies

CUSTOMER
    ↓
Prioritize high-value & high-margin accounts
```

---

# 🚀 Business Recommendations

## 01. Seasonal Sales Strategy

Launch targeted campaigns during weaker periods and strengthen preparation before seasonal peaks.

## 02. SKU Optimization

Prioritize Products 26 and 25 while evaluating low-performing SKUs based on demand and profitability.

## 03. Channel Expansion

Maintain Wholesale as the core revenue engine while developing Export opportunities where margins are attractive.

## 04. Regional Growth

Use California and the West as benchmarks for identifying strategies that can be replicated in weaker regions.

## 05. Customer Value Management

Segment customers based on:

```text
Revenue
+
Profit Margin
```

Then prioritize retention, upselling, cross-selling, and pricing optimization.

## 06. Margin Monitoring

Monitor low-margin accounts and investigate the underlying pricing and cost drivers.

The recommendations above are aligned with the project's documented strategic recommendations.

---

# 📊 Power BI Dashboard

The analytical results were transformed into an interactive **Power BI dashboard** consisting of three pages.

### 01 — Performance Summary

Provides an overview of:

* Revenue performance
* Sales trends
* Product performance
* Channel performance
* Regional performance

### 02 — Customer Segmentation

Focuses on:

* Customer revenue
* Customer profitability
* Revenue ranking
* Revenue vs. margin

### 03 — Revenue Scenario

Provides an interactive analytical view for exploring revenue-related scenarios.

The presentation documents these three dashboard pages as the final visualization output.

---

# 🖼️ Dashboard Preview

> Replace the paths below with your actual screenshot filenames.

### Performance Summary

<p align="center">
  <img src="screenshots/dashboard-overview.png" width="90%">
</p>

### Customer Segmentation

<p align="center">
  <img src="screenshots/customer-segmentation.png" width="90%">
</p>

### Revenue Scenario

<p align="center">
  <img src="screenshots/revenue-scenario.png" width="90%">
</p>

---

# 📁 Repository Structure

```text
Regional-Sales-Analysis/
│
├── 📄 README.md
│
├── 📂 data/
│   └── README.md
│
├── 📂 notebooks/
│   └── Regional_Sales_Analysis.ipynb
│
├── 📂 powerbi/
│   └── Regional_Sales_Analysis.pbix
│
├── 📂 screenshots/
│   ├── dashboard-overview.png
│   ├── customer-segmentation.png
│   └── revenue-scenario.png
│
└── 📂 presentation/
    └── Regional_Sales_Analysis.pptx
```

---

# 🎯 Skills Demonstrated

### Data Analytics

```text
✓ Exploratory Data Analysis
✓ Trend Analysis
✓ Product Analysis
✓ Customer Analysis
✓ Regional Analysis
✓ Profitability Analysis
✓ Correlation Analysis
```

### Data Preparation

```text
✓ Data Cleaning
✓ Data Transformation
✓ Data Integration
✓ Feature Engineering
✓ Data Validation
```

### Business Intelligence

```text
✓ Power BI Dashboard Development
✓ KPI Analysis
✓ Interactive Visualization
✓ Business Storytelling
✓ Dashboard Design
```

### Business & Analytical Thinking

```text
✓ Problem Solving
✓ Business Question Formulation
✓ Insight Generation
✓ Strategic Recommendation
✓ Data-Driven Decision Making
```

---

# 🏆 Project Impact

This project demonstrates the ability to move beyond:

> **"What does the data say?"**

toward:

> **"What should the business do about it?"**

The final analytical workflow connects:

**Raw Data → Clean Data → EDA → Insights → Dashboard → Business Recommendations**

This approach enables stakeholders to independently explore sales performance and use the findings to support sales planning, customer strategy, product optimization, regional expansion, and profitability management.

---

# 👨‍💻 About Me

### Faris Fatur Rohman

**Mathematics Graduate | Aspiring Data Analyst**

I am a Mathematics graduate with a strong interest in **Data Analytics and Data Science**, focused on transforming raw data into meaningful insights that support business decisions.

### Core Skills

```text
Python
SQL
Microsoft Excel
Power BI
Pandas
NumPy
Data Cleaning
EDA
Data Visualization
Business Intelligence
```

I am particularly interested in opportunities where I can combine **mathematical thinking, analytical skills, and business understanding** to solve real-world problems using data.

---

# 💼 Career Interests

Currently interested in opportunities such as:

* Data Analyst
* Junior Data Analyst
* Business Intelligence Analyst
* BI Developer
* Data Science
* Analytics Internship

---

# ⭐ Let's Connect

If you're a recruiter, hiring manager, or fellow data professional interested in discussing this project, feel free to connect.

**I'm always open to learning, collaborating, and solving interesting problems with data.**

---

## 📌 Disclaimer

This project is intended for **portfolio and educational purposes**.

The objective is to demonstrate an end-to-end Data Analytics workflow, including data preparation, exploratory analysis, business insight generation, dashboard development, and strategic recommendations.
