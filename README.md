# 📊 Project_2-KK-Supermarket-Sales-Analysis

## Short Description:
This project aims to analyze the sales data of KK Supermarket to determine whether the business made a profit or not. Additionally, it identifies the key factors that contributed to the profit or loss and explores the reasons behind them.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Insights](#key-insights)
- [Tools & Technologies Used](#tools-technologies-used)
- [How to Run the Project](#how-to-run-the-project)
- [Conclusion](#conclusion)
- [Contact](#contact)

## About the Project
This project analyzes sales data from KK Supermarket to determine whether the business made a profit or not and to identify the key factors that contributed to its performance. The dataset includes transactional details such as date, product, quantity sold, unit price, store location, cashier, total price, and original price.

### Business Questions Addressed:
- What is the total sales revenue?
- Which products, cashiers, and store locations performed the best?
- Are there seasonal trends or patterns in the sales data?
- Which products are consistently high-sellers across different locations?
- What are the peak sales days and times?

The analysis goes beyond descriptive analysis to include trend identification, advanced visualizations (dashboards and heatmaps), and forecasting next month's sales using statistical methods. The ultimate goal is to uncover actionable insights that can guide business decisions and optimize sales strategies.

## Dataset
The dataset for this project was provided by **AIHR - Academy to Innovate HR**, as part of a data analysis training program.

- **Dataset Link**: [Link to Dataset](  https://aihr.ac/3TQ8tXD
) 
- **Size**: 1,002 rows and 13 columns
- **Features** include: Date, Product, Quantity, Unit Price, Store Location, Cashier, Total Price, Original Price, among others.

### Data Quality:
Initially, the dataset contained missing values. These were cleaned and removed using Excel's "Go To Special" function, resulting in a clean dataset ready for analysis.

## Data Cleaning
Several data cleaning and preparation steps were performed to ensure the dataset was analysis-ready:

### Missing Values:
- Identified and removed missing entries using the "Go To Special" function in Excel.

### Data Type Corrections:
- Converted the 'Date' field from number format to a readable short date format.
- Changed 'Unit Price' formatting from general to accounting style for better financial analysis.

### Data Corrections:
- Used the "Find and Replace" function to correct spelling errors and standardize categorical entries.

### Feature Engineering:
- **Days**: Extracted the day of the week from the 'Date' using `=TEXT(Date, "ddd")`.
- **Original Unit Price**: Obtained from business owners to calculate buying prices.
- **Buying Price**: Computed as `Quantity × Original Unit Price`.
- **Total Price (Sales Revenue)**: Calculated as `Quantity × Sold Unit Price`.
- **Profit**: Derived as `Total Price - Buying Price`, indicating the profit per product sold.

## Exploratory Data Analysis (EDA)
Several visualizations and a dashboard were created to explore the supermarket’s sales and profit patterns:

### Dashboard Creation:
- Built a comprehensive dashboard that consolidated key metrics and answers to critical business questions in a single, easy-to-interpret view. 

The dashboard included the following:
- Total Sales
- Sales by Location
- Sales Over Time (Line Chart)
- Product Performance (Bar Chart)
- Cashier Leaderboard (Pie Chart)
- Profit Analysis by Product and Month

### Insights:
- **Product Performance**: Bread generated the highest sales at $9,214, while Apples had the lowest at $6,252.
-   ![product](https://github.com/user-attachments/assets/e1a8a4a5-2096-49d3-9fbc-0d25201b4ae8)

- **Sales by Cashier**: James achieved the highest sales totaling $13,894, while Grace had the lowest at $12,402.
-   ![cashier](https://github.com/user-attachments/assets/bb003939-29b4-4650-9431-4fa359ba3ec3)

- **Monthly Sales Trends**: September ($7,296) and October ($7,273) had the highest monthly sales, while March ($5,871) had the lowest.
-  ![monthly](https://github.com/user-attachments/assets/6127f87d-1e81-45a5-a695-3330bb52b738)

- **Profit per Cashier**: Grace led with a profit of $3,490.69, while Samuel had the lowest profit at $1,412.31.
-    ![cashier_profit](https://github.com/user-attachments/assets/80de83a1-fefb-40d6-b5eb-5a68f2836f62)

- **Profit per Product**: Bread was the most profitable product, generating $3,331 in profit, while Eggs generated the least at $246.
-  ![prod_profit](https://github.com/user-attachments/assets/8e0e9a87-ccd0-4a61-b625-53e1ab420a67)

- **Profit per Month**: November recorded the highest profit at $2,346, while April had the lowest at $163.
- 
![monthly1](https://github.com/user-attachments/assets/536f8e67-6913-47d9-9e4d-4b583a244996)


## Key Insights
- **Overall Profitability**: The supermarket achieved positive profits, with Bread contributing the highest revenue and profit margins.
- **Top Product Performer**: Bread generated the highest total sales ($9,214) and also ranked as the most profitable product ($3,331 in profit).
- **Top Cashier**: James achieved the highest total sales ($13,894), while Grace generated the highest overall profit ($3,490.69).
- **Monthly Sales Trends**: September and October were the best-performing months in terms of sales, with September reaching the highest total ($7,296).
- **Monthly Profitability**: November recorded the highest profit ($2,346), suggesting stronger pricing or sales strategies during that period.
- **Sales Patterns**: Certain products like Bread, Chicken, and Beef consistently performed well across locations, while Apples and Eggs showed lower sales and profitability.

## Tools & Technologies Used
- **Microsoft Excel**: Utilized pivot tables, charts, and various Excel functions for data analysis and visualization.

## How to Run the Project
1. Download the dataset.
2. Open the dataset in Excel.
3. Follow the data cleaning and feature engineering steps as mentioned above.
4. Use pivot tables and charts to replicate the visualizations.
5. Create the final dashboard and analyze the insights as per the steps outlined.

## Conclusion
This analysis provides a comprehensive understanding of KK Supermarket's sales performance and profitability. The key insights gathered can guide future sales strategies, product stocking, and performance optimizations for the business.

## Contact
For further information or questions regarding this project, feel free to reach out:

- Email: [kothroni863@gmail.com](mailto:your-email@example.com)
- GitHub: [Your GitHub Profile](https://github.com/SteveRonald)


