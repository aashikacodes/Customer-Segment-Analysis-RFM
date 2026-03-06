#  RFM Customer Segmentation Analysis

## Project Overview

This project performs **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** on an Online Retail dataset. The goal is to understand customer purchasing behavior, identify high-value customers, detect customers at risk of churn, and generate actionable business insights.

The analysis includes **data cleaning, exploratory data analysis (EDA), RFM score calculation, customer segmentation, and business recommendations**.

---

## Dataset

The dataset used in this project is the **Online Retail dataset**, which contains transaction records for an online retail store.

### Key Features

* **InvoiceNo** – Unique transaction number
* **StockCode** – Product identifier
* **Quantity** – Number of items purchased
* **InvoiceDate** – Date and time of purchase
* **UnitPrice** – Price per unit
* **CustomerID** – Unique identifier for each customer
* **Country** – Country where the customer resides

---

## Project Workflow

### 1. Data Cleaning

* Checked and handled **missing values**
* Removed **duplicate records**
* Converted **date columns to datetime format**
* Created a **Total Revenue column**

### 2. Exploratory Data Analysis (EDA)

Key business questions explored:

* How many unique customers are in the dataset?
* What time period does the data cover?
* What is the total revenue generated?
* How often do customers make purchases?
* How much do customers spend on average?

### 3. RFM Analysis

Customers were segmented using three key metrics:

* **Recency (R)** – How recently a customer made a purchase
* **Frequency (F)** – How often a customer makes purchases
* **Monetary (M)** – How much money a customer spends

Each customer was assigned an **RFM score** based on these metrics.

### 4. Customer Segmentation

Customers were categorized into segments such as:

* Champions
* Loyal Customers
* Potential Loyalists
* New Customers
* Promising Customers
* Needs Attention
* About to Sleep
* At Risk
* Lost Customers
* Others

### 5. Segment Analysis

The project analyzes:

* Revenue contribution by customer segment
* Spending patterns across segments
* Purchase frequency across segments
* Customers likely to churn

### 6. Business Recommendations

Based on the segmentation, different strategies are suggested:

| Segment             | Business Strategy                                   |
| ------------------- | --------------------------------------------------- |
| Champions           | Reward loyalty with VIP offers and exclusive deals  |
| Loyal Customers     | Upselling and cross-selling opportunities           |
| Potential Loyalists | Encourage repeat purchases with targeted promotions |
| New Customers       | Provide onboarding offers and welcome discounts     |
| Promising Customers | Personalized product recommendations                |
| Needs Attention     | Engagement campaigns to increase activity           |
| About to Sleep      | Limited-time offers to re-engage                    |
| At Risk             | Strong win-back campaigns                           |
| Lost Customers      | Re-engagement campaigns or feedback surveys         |

---

## Visualizations

The project includes several visualizations such as:

* Customer distribution across RFM segments
* Revenue contribution by segment
* Spending distribution across segments
* Purchase frequency comparison

---

## Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Project Outcome

This analysis helps businesses:

* Identify **high-value customers**
* Detect **customers likely to churn**
* Understand **customer purchasing behavior**
* Design **targeted marketing strategies**

---

## Future Improvements

Possible extensions of this project include:

* Adding **customer lifetime value (CLV) analysis**
* Building **predictive churn models**
* Creating **interactive dashboards using Power BI or Tableau**

---

## Author

Aashika Jain
