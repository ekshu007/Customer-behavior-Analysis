# Customer-behavior-Analysis
End-to-end data analytics project analyzing customer behavior with Python, PostgreSQL, SQL, and Power BI, including customer segmentation, revenue analysis, and product insights.
# Customer Behavior Analytics

## Data Cleaning, SQL Analysis & Power BI Dashboard

---

## 1. Introduction

Customer purchasing data contains valuable information about spending patterns, product preferences, discount usage, subscription behavior, and customer loyalty.

The objective of this project was to analyze a customer behavior dataset and transform the raw data into meaningful business insights using Python, PostgreSQL, SQL, and Power BI.

The project follows an end-to-end analytics workflow:

**Data Cleaning → Data Storage → SQL Analysis → Visualization → Business Insights**

---

# 2. Project Objective

The main objectives of the project were to:

1. Clean and prepare the customer behavior dataset.
2. Store the cleaned data in PostgreSQL.
3. Use SQL to answer practical business questions.
4. Analyze customer purchasing and spending behavior.
5. Identify popular and highly-rated products.
6. Analyze discount and subscription behavior.
7. Segment customers according to previous purchase behavior.
8. Build an interactive Power BI dashboard.
9. Present the findings through data storytelling.

---

# 3. Tools & Technologies

| Tool       | Usage                        |
| ---------- | ---------------------------- |
| Python     | Data cleaning                |
| Pandas     | Data manipulation            |
| PostgreSQL | Database                     |
| SQL        | Data analysis                |
| SQLAlchemy | Python–PostgreSQL connection |
| Psycopg2   | PostgreSQL driver            |
| Power BI   | Dashboard and visualization  |

---

# 4. Data Preparation

The raw customer behavior dataset was first imported into Python using Pandas.

The data preparation process included:

* Inspecting the dataset
* Understanding column types
* Checking missing values
* Checking duplicate records
* Cleaning categorical values
* Converting columns into suitable data types
* Preparing the final dataset for database storage

The cleaned DataFrame was subsequently loaded into PostgreSQL.

### Database

**Database:** `customer_behavior`

**Table:** `customer`

---

# 5. SQL Analysis

After loading the cleaned dataset into PostgreSQL, SQL was used to answer ten business questions.

The analysis covered:

1. Revenue by gender
2. Discount users with above-average spending
3. Highest-rated products
4. Standard vs Express shipping spending
5. Subscriber vs non-subscriber spending
6. Products with highest discount usage
7. Customer segmentation
8. Top three products within each category
9. Repeat buyers and subscription behavior
10. Revenue contribution by age group

The analysis used aggregation, subqueries, conditional logic, CTEs, and window functions.

---

# 6. Power BI Dashboard

The final output of the project was an interactive Power BI dashboard.

The dashboard converts the SQL analysis into visual insights that can be explored by the user.

## Dashboard Page 1 — Executive Overview

### Purpose

Provide a high-level overview of customer behavior and business performance.

### Recommended visuals

* Total Revenue KPI
* Total Customers KPI
* Average Purchase Amount KPI
* Average Review Rating KPI
* Revenue by Gender
* Revenue by Age Group
* Subscriber vs Non-Subscriber Revenue
* Customer Segment Distribution

### Screenshot

**[INSERT POWER BI OVERVIEW SCREENSHOT HERE]**

---

# 7. Dashboard Page 2 — Customer Analysis

### Purpose

Understand customer characteristics, loyalty, spending, and subscription behavior.

### Recommended visuals

* New vs Returning vs Loyal customers
* Average spend by customer segment
* Revenue by customer segment
* Subscriber vs Non-Subscriber comparison
* Repeat buyer subscription analysis
* Age-group revenue

### Screenshot

**[INSERT CUSTOMER ANALYSIS SCREENSHOT HERE]**

---

# 8. Dashboard Page 3 — Product Analysis

### Purpose

Understand which products are popular, highly rated, and frequently purchased with discounts.

### Recommended visuals

* Top 5 products by average rating
* Top products by purchase count
* Discount rate by product
* Category-wise product performance
* Top 3 products within each category

### Screenshot

**[INSERT PRODUCT ANALYSIS SCREENSHOT HERE]**

---

# 9. Data Storytelling

The dashboard should guide the viewer through the following story:

## Step 1 — Understand the Customer Base

Begin with the total number of customers and their distribution across age groups, gender, and customer segments.

**Screenshot:**

**[INSERT CUSTOMER OVERVIEW SCREENSHOT]**

### Key observation

[Write 1–2 sentences describing the major customer demographic or segment pattern.]

---

## Step 2 — Understand Spending Behavior

Next, examine revenue and average purchase amounts across different customer groups.

**Screenshot:**

**[INSERT SPENDING/REVENUE SCREENSHOT]**

### Key observation

[Write the main spending or revenue insight.]

---

## Step 3 — Understand Customer Loyalty

Compare new, returning, and loyal customers.

**Screenshot:**

**[INSERT CUSTOMER SEGMENT SCREENSHOT]**

### Key observation

[Explain which customer segment dominates and what this could mean for retention.]

---

## Step 4 — Understand Subscription Behavior

Compare subscribers and non-subscribers using customer count, average spending, and total revenue.

**Screenshot:**

**[INSERT SUBSCRIPTION SCREENSHOT]**

### Key observation

[Explain whether subscribers appear to have higher spending/revenue contribution.]

---

## Step 5 — Understand Product Performance

Identify highly-rated and frequently purchased products.

**Screenshot:**

**[INSERT PRODUCT PERFORMANCE SCREENSHOT]**

### Key observation

[Explain the most important product-level finding.]

---

## Step 6 — Understand Discount Behavior

Analyze which products have the highest proportion of discounted purchases.

**Screenshot:**

**[INSERT DISCOUNT ANALYSIS SCREENSHOT]**

### Key observation

[Explain which products are most associated with discounts.]

---

# 10. Key Findings

The analysis can be summarized around five major areas:

### Customer Value

[Insert finding based on your revenue/customer analysis.]

### Loyalty

[Insert finding based on customer segmentation.]

### Subscription

[Insert finding based on subscriber vs non-subscriber analysis.]

### Product Performance

[Insert finding based on product purchases and ratings.]

### Discount Behavior

[Insert finding based on discount rate analysis.]

---

# 11. Business Recommendations

Based on the findings, businesses could consider:

### 1. Strengthen Customer Retention

If loyal customers contribute a large share of revenue, targeted loyalty programs could be used to retain them.

### 2. Optimize Subscription Strategy

If subscribers demonstrate higher spending or revenue contribution, subscription benefits could be promoted to high-frequency customers.

### 3. Optimize Discounts

Products with very high discount usage could be analyzed to determine whether discounts are genuinely driving purchases or simply reducing margins.

### 4. Promote High-Performing Products

Popular and highly-rated products could receive greater visibility through recommendations and promotional campaigns.

### 5. Target High-Value Demographics

Age groups and customer segments with higher revenue contribution could receive more targeted marketing campaigns.

---

# 12. Conclusion

This project demonstrates an end-to-end approach to customer behavior analytics.

Python and Pandas were used for data preparation, PostgreSQL was used for structured data storage, SQL was used to answer business questions, and Power BI was used to transform the analysis into an interactive dashboard.

The project demonstrates how raw customer data can be transformed into actionable insights through a combination of **data cleaning, database management, SQL analytics, and data visualization**.

---

# 13. Future Scope

The project could be extended by implementing:

* RFM customer segmentation
* Customer lifetime value
* Churn prediction
* Purchase prediction
* Cohort analysis
* Customer retention analysis
* Statistical hypothesis testing
* Machine learning-based customer segmentation
* Automated data pipelines
* Real-time or scheduled dashboard refresh
