# Kahoot! Subscription Data Analysis
This project was created as part of a data analyst case task for Kahoot!. The goal was to explore subscription data, prepare it for analysis, and support business recommendations around customer retention, churn, plan tiers, and usage patterns.

The main analysis and final presentation were built in Excel using pivot-table workflows, DAX calculations, and statistical analysis for rapid business exploration and KPI evaluation. This Python notebook was used as a supporting workflow for data validation, cleaning checks, currency normalization, and segmentation testing.

---

## Project Objectives

- Explore subscription and customer-level data
- Validate data quality and missing values
- Normalize monetary values to USD
- Standardize plan names into clearer reporting tiers
- Test usage-based customer segmentation
- Support churn and retention analysis for Customer Success insights

---

## 📊 Dataset
The dataset included 4,293 subscription records and 4,177 unique organizations. It contained information such as:
### Customer & Account Information
- Organization ID
- Country
- Currency
- Sales representative

### Subscription Information
- Plan name
- Quantity
- Subscription status
- Expiration dates
- Previous and current periods

### Financial Metrics
- Unit amount
- Monthly and quarterly revenue-related fields

### Product Usage & Status
- Accepted/not accepted indicators
- Pending status
- Usage-related metrics
- Cancellation indicators

---

## Business Questions Explored

- Which subscription tiers showed the highest churn risk?
- How did customer usage relate to retention behavior?
- Were there meaningful behavioral differences between customer segments?
- Which churn definition best reflected actual customer loss?

---

## Analytical Workflow

### 1. Data Preparation & Validation
- Reviewed missing values and inconsistencies
- Standardized currencies into USD
- Cleaned and grouped subscription-plan variations
- Validated customer and subscription-level relationships

### 2. Exploratory Business Analysis
- Built pivot-table workflows in Excel
- Analyzed churn, retention, and renewal behavior
- Compared performance across plan tiers and customer segments
- Explored revenue distribution and subscription patterns

### 3. KPI & DAX Modeling
- Created DAX measures for churn and retention tracking
- Built calculated metrics for effective churn analysis
- Compared renewal-based vs access-based churn definitions

### 4. Statistical Analysis
- Used regression analysis to explore relationships between usage and retention
- Applied ANOVA testing to evaluate statistically significant differences between customer groups and plan tiers

### 5. Supporting Python Workflow
Python was used to support:
- Data validation
- Currency normalization
- Missing-value checks
- Exploratory testing and preprocessing

---

## Key Insights

- Lower-tier subscription plans showed higher churn tendencies compared to premium plans.
- Usage behavior appeared to correlate with retention likelihood across several customer segments.
- Different churn definitions produced noticeably different interpretations of customer loss.
- Standardizing currencies and plan naming significantly improved consistency across KPI reporting.

---

## 🛠 Tools & Libraries
- Python (`pandas`, `matplotlib`, `seaborn`, `numpy`, `scipy`)
- Jupyter Notebook
- Excel
- Power Pivot & DAX

---

## 📌 Key Learnings
- Learned how important data standardization is before analysis, especially when working with multiple currencies and inconsistent plan naming conventions.
- Improved my ability to combine Python and Excel efficiently, using Python for validation and preprocessing while leveraging Excel for rapid business exploration and presentation building.
- Practiced translating raw subscription data into business-oriented insights related to churn, retention, and customer segmentation.
- Gained experience structuring exploratory analysis under time constraints while still maintaining a clear analytical workflow and documentation process.

---
