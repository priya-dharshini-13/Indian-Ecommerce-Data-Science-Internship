# Indian E-Commerce Data Science Internship

## Project Overview

This repository contains my work completed during my Data Science Internship, based on the **Indian E-Commerce Sales Analytics Dataset**.

The project focuses on analyzing e-commerce customer and sales data using Python. The internship work was completed week by week, covering data cleaning, exploratory data analysis, data visualization, storytelling, statistical analysis, and hypothesis testing.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

## Project Structure


Indian-Ecommerce-Data-Science-Internship/
│
├── week1/
│   ├── Week1_EDA.ipynb
│   ├── screenshots/
│   └── Week1 Task.docx
│
├── week2/
│   ├── Week2_Visualization.ipynb
│   ├── visualization images/
│   └── Week2 Task.docx
│
├── week3/
│   ├── Week3_Hypothesis_Testing.ipynb
│   ├── h1_upi_vs_cod.png
│   ├── h2_order_status_payment.png
│   ├── h3_tier_anova.png
│   ├── h4_coupon_vs_no_coupon.png
│   └── Week3 Task.docx
│
└── README.md

# Week 1 - Data Cleaning, EDA and Analysis

The first week focused on preparing the e-commerce dataset for analysis.

### Work completed

* Loaded customer, product and sales datasets using Pandas.
* Checked data structure, missing values and duplicates.
* Converted date columns into appropriate datetime format.
* Handled missing coupon values.
* Removed invalid records with negative order values.
* Performed exploratory data analysis.
* Studied customer, product and sales-related patterns.
* Created visualizations to understand important trends.

### Dataset after cleaning

* Customers: 40,000 records
* Products: 2,000 records
* Sales: 249,995 valid records

---

# Week 2 - Advanced Data Visualization and Storytelling

The second week focused on creating meaningful visualizations and communicating insights to a non-technical audience.

### Work completed

* Analyzed monthly revenue trends.
* Compared revenue across states.
* Studied customer age groups and customer tiers.
* Analyzed product categories.
* Examined payment modes and order status.
* Created visualizations using Matplotlib and Seaborn.
* Used charts to communicate business insights clearly.

### Key visualizations

* Monthly Revenue Trend
* Top 10 States by Revenue
* Customer Age Group and Tier Analysis
* Product Category Analysis
* Payment Mode and Order Status Analysis

---

# Week 3 - Statistical Analysis and Hypothesis Testing

The third week focused on applying statistical techniques to validate business-related assumptions.

Four hypotheses were tested using statistical methods.

### Hypothesis 1 - UPI vs COD

**Question:** Do UPI users have a higher average order value than COD users?

**Test:** Independent t-test

**Result:** UPI users had a significantly higher average order value than COD users.

---

### Hypothesis 2 - Payment Mode vs Order Status

**Question:** Is order status related to payment mode?

**Test:** Chi-Square Test of Independence

**Result:** No statistically significant association was found between payment mode and order status.

---

### Hypothesis 3 - Customer Tier

**Question:** Does average order value differ across Silver, Gold and Platinum customers?

**Test:** One-Way ANOVA with Tukey HSD

**Result:** Significant differences were found across the customer tiers, with Platinum customers having the highest average order value.

---

### Hypothesis 4 - Coupon Usage

**Question:** Do customers who use coupons spend more?

**Test:** Independent t-test

**Result:** A statistically significant difference was found, but the practical effect was negligible. Non-coupon users had a slightly higher average order value.

---

## Dataset Note

The original CSV datasets (`customers.csv`, `products.csv`, and `sales.csv`) are **not included in this GitHub repository because of GitHub file-size limitations**.

The datasets were used locally during the analysis. The complete analysis code, notebooks, visualizations, and reports are included in this repository.

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Data visualization
* Statistical hypothesis testing
* Independent t-tests
* Chi-Square testing
* One-Way ANOVA
* Tukey HSD post-hoc analysis
* Effect size interpretation
* Business-oriented data interpretation
* Data storytelling using Python

---

## Overall Insights

The analysis provided several useful insights into e-commerce customer behaviour:

* UPI users showed higher average order values than COD users.
* Payment mode was not significantly associated with order status.
* Customer tier showed significant differences in spending behaviour.
* Platinum customers generated substantially higher average order values.
* Coupon usage produced a statistically significant but negligible difference in order value.

These findings demonstrate how statistical analysis can support better customer segmentation, payment strategies, loyalty programs and promotional decisions.

---

## Author

**Priya Dharshini S.**

B.C.A. Student
Data Science Intern



