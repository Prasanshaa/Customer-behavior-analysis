
# Customer Behavior Analysis

A data analytics project focused on analyzing customer purchasing behavior, spending patterns, subscription trends, product performance, and revenue insights using Python, PostgreSQL, and Power BI.

## Project Overview

This project analyzes customer shopping data to identify meaningful business insights related to customer behavior, purchase patterns, product performance, discounts, subscriptions, and revenue. The workflow combines Python for data cleaning and preparation, PostgreSQL for SQL-based analysis, and Power BI for interactive dashboard development.

## Objectives

- Analyze customer purchasing behavior and spending patterns.
- Identify revenue trends across categories, seasons, and age groups.
- Compare subscribed and non-subscribed customers.
- Analyze product performance, discounts, and customer reviews.
- Segment customers based on their previous purchase history.
- Build an interactive Power BI dashboard to communicate key insights.

## Dataset

- **Records:** 3,900
- **Columns:** 18
- **Domain:** Customer shopping behavior
- **Data preparation:** Python and Pandas

The dataset includes information related to customer demographics, purchases, products, discounts, shipping methods, reviews, subscriptions, and previous purchases.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data cleaning and preparation |
| Pandas | Data manipulation and analysis |
| PostgreSQL | Database storage and SQL analysis |
| SQLAlchemy | Connecting Python with PostgreSQL |
| SQL | Data analysis and business queries |
| Power BI | Interactive dashboard and visualization |
| Jupyter Notebook | Data analysis workflow |

## Project Workflow

1. Imported the customer shopping dataset into Python.
2. Cleaned and prepared the data using Pandas.
3. Standardized relevant data fields and handled missing values.
4. Connected Python to PostgreSQL using SQLAlchemy.
5. Loaded the prepared dataset into PostgreSQL.
6. Performed SQL-based analysis using aggregations, CTEs, subqueries, CASE statements, and window functions.
7. Created an interactive Power BI dashboard to visualize key performance indicators and customer insights.

## Key SQL Analysis

The project includes SQL analysis covering:

- Revenue analysis by gender and age group.
- Subscription status and customer spending comparison.
- Total revenue and average spending analysis.
- Product performance based on average review ratings.
- Top products by discount rate.
- Customer segmentation using previous purchase history.
- Top products within categories using window functions.
- Comparison of repeat buyers and subscription status.
- Revenue ranking by product within each category.
- Average purchase amount by shipping type.

## Power BI Dashboard

The interactive dashboard presents key performance indicators and visualizations, including:

- Total customer count.
- Average purchase amount.
- Average review rating.
- Total revenue.
- Revenue by category and season.
- Customer analysis by subscription status and gender.
- Revenue distribution by age group.
- Payment method analysis.
- Shipping type analysis.

### Dashboard Preview

![Customer Behavior Dashboard](Customer%20Behavior%20Dashboard%20img.png)

## Project Files

```text
customer-behavior-analysis/
│
├── Customer Behavior analysis.ipynb
├── cust_behavior_postgre.sql
├── Customer Behavior Dashboard img.png
├── .gitignore
└── README.md
```

## Key Skills Demonstrated

- Data cleaning and preprocessing using Python and Pandas.
- Connecting Python to PostgreSQL using SQLAlchemy.
- SQL aggregations, CTEs, subqueries, and CASE statements.
- Window functions such as ROW_NUMBER() and DENSE_RANK().
- Customer segmentation and revenue analysis.
- Data visualization and dashboard development in Power BI.
- Translating business questions into data-driven analysis.

## How to Use This Project

### 1. Clone the repository

```bash
git clone https://github.com/Prasanshaa/Customer-behavior-analysis.git
```

### 2. Install the required Python libraries

```bash
pip install pandas sqlalchemy psycopg2-binary python-dotenv
```

### 3. Configure your local PostgreSQL database

Store your database credentials in a local `.env` file. **Do not upload the `.env` file to GitHub.**

### 4. Run the project

Open the Jupyter Notebook and run the data preparation and analysis workflow.

Execute the SQL queries in PostgreSQL and open the Power BI dashboard for visualization.

## Learning Outcomes

Through this project, I strengthened my practical skills in data preparation, exploratory analysis, SQL querying, relational databases, customer behavior analysis, and dashboard development. The project helped me understand how raw data can be transformed into structured insights for business decision-making.

## Author

**Prasansha Madeshia**

- LinkedIn: [Prasansha Madeshia](https://www.linkedin.com/in/prasansha-madeshia-b8922224/)
- GitHub: [Prasanshaa](https://github.com/Prasanshaa)

## Disclaimer

This project is created for learning and portfolio purposes. The analysis is based on the available dataset and is intended to demonstrate data analytics and visualization skills.
