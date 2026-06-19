# Coffee Shop Sales Analysis

## Project Overview
This project is an end-to-end data analysis of a coffee shop's transactional data. By analyzing over 149,000 sales records, this project uncovers actionable business insights regarding customer purchasing behaviors, peak business hours, monthly revenue trends, and top-performing products. 

## Tech Stack
* Language: Python
* Libraries: Pandas (Data manipulation), NumPy, Matplotlib & Seaborn (Data visualization)
* Environment: Jupyter Notebook (.ipynb)

## Dataset Description
The analysis is based on the `Coffee Shop Sales.csv` dataset, which contains 149,116 transactions. Key data points include:
* Transaction Details: Date, Time, Quantity, Unit Price
* Store Info: Store ID, Store Location
* Product Details: Category, Type, Detail (e.g., Coffee, Gourmet brewed coffee, Ethiopia Rg)

## Project Workflow
1. Data Import & Cleaning: Handled data types, checked for missing values, and ensured clean data for analysis.
2. Feature Engineering: Extracted valuable features such as:
   * Revenue: Calculated total revenue per transaction (`transaction_qty` * `unit_price`).
   * Date/Time Metrics: Extracted month, day, and hour to analyze temporal trends.
3. Exploratory Data Analysis (EDA) & Visualization: Built custom, clean visual charts to display key metrics.

## Key Findings & KPIs
* Total Orders: 149,116
* Total Items Sold: 214,470
* Top Product Categories (by Revenue):
  1. Coffee: $269,952.45
  2. Tea: $196,405.95
  3. Bakery: $82,315.64
* Top 3 Individual Products:
  1. Barista Espresso ($91,406)
  2. Brewed Chai Tea ($77,081)
  3. Hot Chocolate ($72,416)

## Visualizations Included
* Hourly Orders: Identifying the busiest hours of the day to optimize staff scheduling.
* Monthly Revenue Analysis: Tracking business growth and seasonal trends.
* Total Orders & Revenue by Product Category: Understanding what drives the most sales volume vs. actual revenue.
* Top 10 Products: A breakdown of the absolute best-selling items.

## How to Run the Project
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/priyanshchauhan026/Coffee_Shop_Sales_Analysis.git](https://github.com/priyanshchauhan026/Coffee_Shop_Sales_Analysis.git)
