# Customer Shopping Behaviour Analysis

-- Project Overview

The **Customer Shopping Behaviour Analysis** project focuses on understanding customer purchasing patterns, spending habits, product preferences, subscription behaviour, and revenue trends.

This project uses Python, SQL, and Power BI to transform raw customer shopping data into meaningful business insights that can help businesses understand their customers and make better data-driven decisions.

 -- Business Problem

Businesses collect large amounts of customer shopping data, but understanding customer behaviour and purchasing patterns can be challenging.

This project aims to answer important business questions:

- Which gender generates more revenue?
- How do discounts influence customer spending?
- Which products receive the highest customer ratings?
- Does shipping type affect average purchase amounts?
- How do subscribers and non-subscribers differ in spending?
- Which products depend most on discounts?
- How can customers be segmented based on previous purchases?
- Which products are most popular in each category?
- How does subscription status relate to repeat purchases?
- Which age group generates the highest revenue?

-- Technologies Used

- **Python:** Data cleaning and preprocessing.
- **Pandas:** Data manipulation and analysis.
- **Jupyter Notebook:** Python-based analysis.
- **SQL Server (SSMS):** Business queries and data analysis.
- **Power BI:** Interactive data visualization and dashboard development.
- **Microsoft Excel:** Supporting data handling.

 -- Project Workflow

1. Data Cleaning & Preparation (Python)

Used Python and Pandas to prepare the raw dataset.

Tasks performed:

- Loaded and explored the dataset.
- Checked missing values.
- Handled missing review ratings using category-wise median.
- Renamed and standardized column names.
- Created age groups using quartiles.
- Converted purchase frequency into days.
- Removed the unnecessary promo_code_used column.
- Exported the cleaned dataset as a CSV file.

2. SQL Business Analysis

Used SQL Server to perform 10 business analyses:

1. Revenue Analysis by Gender
2. Discount and Spending Analysis
3. Product Rating Analysis
4. Shipping Analysis
5. Subscription Analysis
6. Discount Dependency Analysis
7. Customer Segmentation
8. Product Popularity Analysis
9. Repeat Buyer Analysis
10. Age Group Revenue Analysis

SQL concepts used:

- SELECT, WHERE, GROUP BY
- ORDER BY
- Aggregate Functions (SUM, AVG, COUNT)
- CASE Statements
- Common Table Expressions (CTEs)
- Subqueries
- Window Functions (ROW_NUMBER)
- ROUND and TRY_CAST

 3. Power BI Dashboard

Developed a customer shopping behaviour dashboard to visualize important business metrics.

**Key Performance Indicators (KPIs):**

- Total Customers: 3,900
- Total Revenue: $233,081
- Average Purchase Amount: $59.76
- Average Review Rating: 3.75

**Dashboard Analysis:**

- Customer distribution by subscription status.
- Revenue comparison by gender.
- Top 10 products by revenue.
- Revenue by product category.
- Revenue by customer age group.

 -- Key Insights

The dashboard highlights:

- A comparison of male and female customer revenue contribution.
- The distribution of subscribers and non-subscribers.
- Revenue contribution across different product categories.
- Purchasing patterns across customer age groups.
- Top-performing products based on revenue.

#⚙️ How to Use This Project

Follow these steps to explore the project:

**Step 1: Clone the Repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Install Required Python Libraries**

```bash
pip install pandas numpy jupyter
```

**Step 3: Run the Python Notebook**

- Open Jupyter Notebook.
- Open `customer shopping behaviour.ipynb`.
- Keep the original CSV dataset in the correct folder.
- Run the notebook cells sequentially.
- Generate the cleaned CSV file.

**Step 4: Run SQL Analysis**

- Open SQL Server Management Studio (SSMS).
- Create or select your database.
- Import the cleaned CSV dataset.
- Make sure the table name is `cleaned_customer behavior`.
- Open `Customer Shopping behavior.sql`.
- Execute the queries to explore business insights.

**Step 5: Explore the Power BI Dashboard**

- Open the Power BI project file, if included.
- Connect it to the cleaned dataset.
- Refresh the data.
- Explore customer behaviour and revenue visualizations.

## -- Project Objective

The main objective of this project is to demonstrate practical data analytics skills by combining Python, SQL, and Power BI to solve real-world business problems and convert raw data into actionable insights.

## 👨‍💻 Author

Aspiring Data Analyst | BCA Student

**Skills:** Python | SQL | Power BI | MS Excel | Basic Statistics

