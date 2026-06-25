# 📊 Vendor Performance Analysis

## Overview

This project analyzes vendor performance, inventory efficiency, pricing strategies, and profitability using retail sales and purchase data. The objective is to identify opportunities to improve business profitability by evaluating vendor contributions, inventory turnover, bulk purchasing benefits, and pricing effectiveness.

The analysis combines Exploratory Data Analysis (EDA), statistical analysis, correlation analysis, and business insights to support data-driven decision-making.

---

## Business Problem

Retail and wholesale businesses often face challenges such as:

* Low-performing products with poor sales
* Vendor dependency risks
* High inventory holding costs
* Inefficient pricing strategies
* Reduced profitability

This project addresses these challenges by answering key business questions related to vendor performance and inventory management.

---

## Objectives

* Identify brands requiring promotional or pricing adjustments.
* Find the top vendors contributing to sales and profits.
* Analyze the impact of bulk purchasing on unit costs.
* Measure inventory turnover and identify slow-moving inventory.
* Compare profitability between high-performing and low-performing vendors.
* Generate actionable business recommendations.

---

## Dataset Features

The analysis includes variables such as:

* Vendor Number
* Vendor Name
* Brand
* Purchase Price
* Actual Price
* Purchase Quantity
* Purchase Dollars
* Sales Quantity
* Sales Dollars
* Sales Price
* Excise Tax
* Freight Cost
* Gross Profit
* Profit Margin
* Stock Turnover
* Sales-to-Purchase Ratio

---

## Exploratory Data Analysis

The project performs:

* Summary statistics
* Missing and inconsistent data handling
* Outlier detection
* Distribution analysis
* Correlation heatmap
* Inventory analysis
* Profitability analysis

Key observations include:

* Negative gross profit transactions
* Zero-sales products
* Premium-priced product outliers
* Large variation in freight costs
* Significant differences in inventory turnover across vendors

---

## Data Cleaning

The following records were removed to improve analysis quality:

* Gross Profit ≤ 0
* Profit Margin ≤ 0
* Total Sales Quantity = 0

This ensured the analysis focused on profitable and completed sales transactions.

---

## Key Business Questions

### 1. Which brands require promotional or pricing adjustments?

* Identified **198 brands** with low sales but high profit margins.
* These brands have strong profitability potential but require better market exposure.

---

### 2. Which vendors contribute the most?

The analysis revealed that:

* Top 10 vendors contribute **65.69%** of total purchases.
* Remaining vendors contribute **34.31%**.

This indicates a heavy dependency on a small number of suppliers.

---

### 3. Does bulk purchasing reduce costs?

Yes.

Average purchase price by order size:

| Order Size | Average Unit Cost |
| ---------- | ----------------: |
| Small      |            $39.06 |
| Medium     |            $15.49 |
| Large      |            $10.78 |

Large purchases reduce unit costs by nearly **72%**.

---

### 4. Which vendors have poor inventory turnover?

Findings include:

* Total unsold inventory value: **$2.71 Million**
* Several vendors exhibit slow inventory movement, increasing storage costs and reducing cash flow.

---

### 5. How do high-performing and low-performing vendors compare?

| Vendor Group           | Average Profit Margin |
| ---------------------- | --------------------: |
| Top Vendors            |                31.17% |
| Low-performing Vendors |                41.55% |

Although low-performing vendors maintain higher profit margins, they struggle to generate sufficient sales volume.

---

### 6. Is the difference statistically significant?

A hypothesis test confirmed that the profit margins of top-performing and low-performing vendors differ significantly, indicating distinct profitability models.

---

## Visualizations

The project includes:

* Distribution plots
* Correlation heatmap
* Scatter plots
* Vendor contribution chart
* Inventory turnover analysis
* Profit margin comparison
* Confidence interval visualization

---

## Business Insights

* Optimize pricing for high-margin, low-sales products.
* Diversify vendor partnerships to reduce supplier dependency.
* Increase bulk purchasing where economically beneficial.
* Improve inventory turnover by reducing slow-moving stock.
* Strengthen marketing and distribution strategies for low-performing vendors.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## Project Workflow

```
Business Problem
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Business Insights
        │
        ▼
Recommendations
```

---

## Results

This analysis demonstrates how data analytics can support strategic business decisions by:

* Improving vendor management
* Reducing inventory costs
* Increasing profitability
* Optimizing pricing strategies
* Supporting better procurement decisions

---

## Future Improvements

* Develop an interactive Power BI dashboard.
* Build demand forecasting models.
* Apply machine learning for vendor performance prediction.
* Automate reporting using Python.
* Perform customer segmentation alongside vendor analysis.

---

## Author

**Gurpreet Singh**

If you found this project useful, consider giving it a ⭐ on GitHub.
