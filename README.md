# Restaurant Sales Analysis

This project analyzes restaurant transaction data to uncover sales trends, menu performance, customer behavior, and temporal patterns. Using Python and data visualization libraries, the goal is to extract actionable insights that can help optimize operations and boost revenue.

## Project Overview

The dataset contains detailed records of customer orders, including information about the menu item sold, quantity, pricing, time of purchase, and more. Through structured analysis and visualizations, this project reveals patterns in item performance, peak sales hours, and customer demand cycles.

## About the Dataset

- **File Name:** `Resturanr_Sales_Data.xlsx`  
- **Dataset Type:** Transactional sales data  
- **Key Features:**
  - `order_id` — Unique identifier for each order  
  - `item` — Menu item sold  
  - `quantity` — Number of units sold  
  - `price` — Price per item or per order  
  - `timestamp` — Date and time of the order  
  - `branch` — Store location (if applicable)  

This structured dataset is used to analyze sales patterns across time, products, and outlets.

## Tasks Performed

- Imported and inspected the dataset  
- Cleaned data by removing nulls and duplicates  
- Parsed `timestamp` to extract:
  - Date
  - Hour
  - Day of week
  - Month
- Created a `total_sales` column (quantity × price)  
- Aggregated and visualized:
  - Total revenue by item  
  - Number of orders per hour and day  
  - Best-selling and least-selling menu items  
  - Sales trends over time (daily, weekly, monthly)  
  - Revenue performance across different branches  

## Key Findings

- A small number of menu items generate the majority of total revenue.  
- Sales peak during lunch and dinner hours, showing clear daily demand cycles.  
- Weekends consistently outperform weekdays in total revenue.  
- Middle-priced, high-frequency items drive more total revenue than premium items with low order volume.  
- Certain branches have significantly higher average revenue per order, suggesting better customer conversion or upselling.

## Interesting Insight

Items with moderate pricing and consistent popularity contribute more to overall revenue than higher-priced items with low sales. This emphasizes the impact of volume-driven sales and suggests that optimizing mid-range menu items can be more profitable than focusing on premium dishes alone.

## Conclusion

This analysis highlights crucial aspects of the restaurant’s performance, including product-wise revenue contribution, time-based demand trends, and location-based sales behavior. These insights can guide menu optimization, staffing decisions, pricing strategies, and targeted promotions to increase profitability and improve operational efficiency.


## Author
**Devansh Singh Tomar**

## Requirements

- **Python 3.12.0**
- **Jupyter Notebook**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/bersercz/Resturant_sales_Analysis.git
   cd Resturant_sales_Analysis
