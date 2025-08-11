📊 Amazon Product Data Analysis
📌 Project Overview
This project performs data analysis on an Amazon product dataset to extract useful insights such as:

Most popular products by review count

Price distribution and averages by category

Rating trends across categories

Discount patterns

Popularity trends (reviews) by category

The dataset contains product details, prices, ratings, discounts, reviews, and categories.

📂 Dataset Information
The dataset (amazon.csv) contains the following relevant columns:

Column Name	Description
product_id	Unique identifier for each product
product_name	Name of the product
category	Category path of the product
discounted_price	Current selling price (₹)
actual_price	Original product price (₹)
discount_percentage	Discount percentage applied
rating	Average customer rating
rating_count	Number of ratings/reviews
about_product	Short product description
product_link	Amazon product page link

🛠 Tools & Libraries Used
Python – Data processing & analysis

Pandas – Data manipulation & cleaning

Matplotlib – Data visualization

Jupyter Notebook / Google Colab – Interactive environment for running the analysis

📊 Analysis Performed
1. Data Cleaning
Removed currency symbols (₹) and commas from discounted_price and actual_price

Removed percentage sign (%) from discount_percentage

Converted rating_count from string to numeric

Converted rating to numeric (handling missing values)

2. Insights & Visualizations
Top 10 Most Reviewed Products

Sorted products by rating_count

Bar chart showing the top 10 products with the most reviews

Average Discounted Price by Category

Grouped by category and calculated average discounted price

Bar chart visualization

Average Rating by Category

Grouped by category and calculated average rating

Orange-colored bar chart visualization

Discount Percentage Distribution

Histogram showing the distribution of product discounts

Popularity Trend (Reviews by Category)

Grouped categories by total rating_count

Line chart showing popularity trends across categories

📈 Example Charts Generated
Bar Chart: Top 10 Most Reviewed Products

Bar Chart: Average Price per Category

Bar Chart: Average Rating per Category

Histogram: Discount Distribution

Line Chart: Popularity Trend by Category

📌 How to Run the Project
Install required libraries:

bash
Copy
Edit
pip install pandas matplotlib
Open Jupyter Notebook or Google Colab

Upload the amazon.csv file

Run the notebook cells to:

Clean the data

Generate visualizations

View insights

📜 Outcome
By the end of this analysis, you’ll have:

A clean dataset ready for further analysis

5 visualizations giving insights into product popularity, pricing, and discounts

An understanding of which categories/products are most engaging to customers

📎 Deliverables
analysis_notebook.ipynb – Jupyter Notebook with full code & charts

amazon.csv – Dataset used

README.md – Project documentation (this file)

