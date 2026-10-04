# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer preferences, sales trends, and business opportunities.

The project follows an end-to-end data analytics workflow, starting from data loading and cleaning in Python, followed by exploratory data analysis, SQL-based analysis, and an interactive Power BI dashboard.

The analysis also includes a detailed project report and presentation covering the key findings and business recommendations.

---

## Dataset

The dataset contains **3,900 customer shopping records** with information related to:

* Customer demographics
* Products and categories
* Purchase amounts
* Discounts
* Ratings
* Subscription status
* Shipping type
* Payment methods
* Previous purchases
* Purchase frequency
* Seasonal information

The data was cleaned and transformed before performing SQL analysis and visualization.

---

## Tools & Technologies

* **Python** – Data loading, cleaning, transformation, and EDA
* **Pandas** – Data manipulation and analysis
* **PostgreSQL / SQL** – Data storage and business analysis
* **Power BI** – Interactive dashboard and visualization
* **Excel** – Initial data inspection and supporting analysis
* **Gamma** – Project presentation (PPT)
* **GitHub** – Project documentation and version control

---

## Project Steps

### 1. Data Loading

The dataset was loaded into Python using Pandas and inspected to understand its structure, columns, data types, and missing values.

### 2. Exploratory Data Analysis

Performed EDA to understand:

* Dataset structure
* Customer demographics
* Product categories
* Purchase patterns
* Spending behavior
* Ratings
* Discounts
* Subscription behavior

### 3. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing values
* Correcting column names
* Checking data types
* Removing redundant information
* Creating useful derived columns
* Categorizing customers based on age and purchase frequency

### 4. SQL Analysis

The cleaned dataset was loaded into a relational database and analyzed using SQL.

Business questions included:

* Revenue by gender
* Discount usage and spending behavior
* Top-rated products
* Shipping type comparison
* Subscriber vs. non-subscriber behavior
* Products with the highest percentage of discounted purchases
* Customer loyalty segments
* Top products by category
* Subscription likelihood based on purchase history
* Revenue by age group

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to visualize important business metrics and trends.

The dashboard helps users understand:

* Customer purchasing behavior
* Product performance
* Revenue patterns
* Discount usage
* Subscription behavior
* Customer segments

### 6. Report & Presentation

A detailed project report was created to document the analysis, findings, and recommendations.

A presentation was also created using Gamma to communicate the project workflow, key insights, and business recommendations in a concise format.

---

## Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior and allows users to explore important metrics and patterns.

**Dashboard file:** `powerbi/customer_shopping_behavior_dashboard.pbix`

> Add a screenshot of your Power BI dashboard here.

Example:

```text
![Power BI Dashboard](screenshots/dashboard.png)
```

---

## Results & Key Insights

The analysis helped identify important patterns in customer purchasing behavior, including:

* Differences in purchasing behavior between customer segments
* Products and categories with strong customer demand
* Relationship between discounts and purchasing behavior
* Differences between subscribers and non-subscribers
* Customer groups with higher purchasing activity
* Impact of shipping preferences on purchase amounts
* High-performing products and categories

These insights can support better marketing, customer retention, pricing, and product strategies.

---

## Business Recommendations

Based on the analysis:

* **Boost Subscriptions** – Promote exclusive benefits to increase subscription adoption.
* **Customer Loyalty Programs** – Reward repeat customers and encourage higher customer retention.
* **Review Discount Policy** – Balance discount strategies with revenue and profitability goals.
* **Product Positioning** – Promote highly rated and popular products.
* **Targeted Marketing** – Focus marketing campaigns on high-value customer segments.
* **Customer Segmentation** – Develop personalized strategies based on customer purchasing behavior.

---

## Project Files

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior_cleaned.csv
│
├── sql/
│   └── customer_shopping_behavior_analysis.sql
│
├── powerbi/
│   └── customer_shopping_behavior_dashboard.pbix
│
├── report/
│   └── customer_shopping_behavior_report.pdf
│
└── README.md
```

---

## How to Run

### Python Analysis

1. Download or clone this repository.
2. Open the Python/Jupyter Notebook.
3. Make sure the required Python libraries are installed.

```bash
pip install pandas numpy matplotlib
```

4. Load the dataset from the `data` folder.
5. Run the notebook cells sequentially.

### SQL Analysis

1. Open PostgreSQL, MySQL, or SQL Server.
2. Create a database and table.
3. Import the cleaned CSV dataset.
4. Run the SQL queries from:

```text
sql/customer_shopping_behavior_analysis.sql
```

### Power BI

1. Open Power BI Desktop.
2. Open:

```text
powerbi/customer_shopping_behavior_dashboard.pbix
```

3. If required, update the data source connection.
4. Refresh the data and explore the dashboard.

---

## Project Outcome

This project demonstrates an end-to-end data analytics workflow involving **Python, SQL, data cleaning, exploratory data analysis, business analysis, Power BI visualization, reporting, and presentation**.

It showcases the ability to transform raw customer data into meaningful business insights and actionable recommendations.

---

## License

This project is licensed under the **MIT License**.

