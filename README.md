
# Customer Shopping Behavior Analysis 📊

An end-to-end Data Analytics project to analyze customer shopping patterns, purchasing trends, customer segments, and revenue drivers using Python, PostgreSQL, and Power BI.

## 🎯 Project Objective

To understand customer shopping behavior and generate actionable business insights to improve sales, customer engagement, and customer loyalty.

## 🛠️ Tech Stack

- **Python:** Pandas, NumPy
- **SQL:** PostgreSQL
- **Visualization:** Power BI
- **Environment:** Jupyter Notebook

## 📌 Project Workflow

### 1. Data Preparation & EDA (Python)
- Imported and explored the dataset.
- Handled missing values and cleaned data.
- Performed feature engineering.
- Connected Python with PostgreSQL.

### 2. Data Analysis (PostgreSQL)
- Revenue analysis by gender and age group.
- High-spending customers using discounts.
- Subscribers vs. non-subscribers analysis.
- Customer segmentation (New, Returning, Loyal).
- Top-rated and best-selling products.
- Repeat purchase analysis.


### 3. Dashboard & Visualization (Power BI)

Created an interactive **Customer Behavior Dashboard** in Power BI to visualize customer purchasing patterns and business performance.

**Dashboard Highlights:**
- **Key KPIs:** Total Customers (3.9K), Average Purchase Amount ($59.76), and Average Review Rating (3.75).
- **Subscription Analysis:** Percentage of customers by subscription status (Yes/No).
- **Revenue by Category:** Comparison of revenue across product categories.
- **Sales by Category:** Analysis of sales performance across categories.
- **Revenue by Age Group:** Revenue contribution from different customer age groups.
- **Sales by Age Group:** Comparison of customer sales across age groups.

**Interactive Filters:**
- Subscription Status
- Gender
- Product Category
- Shipping Type

The dashboard enables stakeholders to explore customer behavior, compare sales performance, and make data-driven business decisions.


## 📊 Dataset Overview

| Metric | Details |
|---|---|
| Total Records | 3,900 |
| Total Columns | 18 |
| Missing Values | 37 (Review Rating) |
| Data Domain | Retail Customer Shopping |

## 📈 Key Findings

- Analyzed 3,900 customer transactions.
- Average purchase amount: **$59.76**.
- Average review rating: **3.75**.
- Identified 3,116 Loyal, 701 Returning, and 83 New customers.
- Analyzed customer subscription, discount usage, shipping preferences, and product performance.

## 💡 Business Recommendations

- Promote exclusive subscription benefits.
- Introduce customer loyalty rewards.
- Optimize discount strategies.
- Highlight top-rated and best-selling products.
- Focus marketing on valuable customer segments.

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
└── README.md
```

## 🚀 How to Run

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Shopping-Behavior-Analysis.git
```

**2. Install dependencies**

```bash
pip install pandas numpy sqlalchemy psycopg2-binary jupyter
```

**3. Run the Jupyter Notebook**

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells.

**4. PostgreSQL Analysis**

Configure your database connection and execute `customer_behavior_sql_queries.sql`.

**5. Power BI Dashboard**

Open `customer_behavior_dashboard.pbix` using Power BI Desktop.
