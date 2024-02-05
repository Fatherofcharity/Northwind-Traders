# Power BI Dashboard of Northwind Traders

This repository contains a Power BI dashboard that I created using the Northwind Traders dataset from Kaggle. The dataset contains sales data for a fictitious company that sells speciality foods. I performed some data cleaning and transformation to prepare the data for analysis. I also used DAX calculations to derive some key metrics, such as net revenue, total revenue, and discount percentage. The dashboard shows the sales performance of different products, categories, regions, and employees, as well as the trends and patterns over time.

## Data Preparation

I used Power Query Editor in Power BI Desktop to clean and transform the data. Some of the steps I took include:

- Renaming and reordering the columns for clarity and consistency
- Changing the data types and formats of some columns
- Removing unnecessary columns and rows
- Splitting the OrderDate column into Year, Month, and Day columns
- Creating a Calendar table to enable date filtering and grouping
- Merging the tables based on the key columns
- Creating a Star schema with Products as the fact table and the other tables as dimension tables

## Data Analysis

I used Power BI Desktop to create various visuals and measures to analyze the data. Some of the measures I created using DAX are:

- Net Revenue 
- Total Revenue 
- Discount Percentage 
- Average Order Quantity

Some of the visuals I created are:

- A line chart showing the net revenue by year and month
- A clustered column chart showing the net revenue by category and region
- A pie chart showing the shipping costs by company
- A clustered column showing the net revenue by employee
- A card showing the total net revenue
- A slicer to filter the data by date range

## Dashboard Preview

Here is a screenshot of the dashboard:
https://github.com/Fatherofcharity/Northwind-Traders/blob/main/Northwind%20Traders%20Dashboard.png


## How to Use

To use this dashboard, you need to have Power BI Desktop and Power BI service accounts. You can download the Power BI Desktop file (.pbix) from this repository and open it in Power BI Desktop. You can then publish the file to the Power BI service and create a dashboard from the report. Alternatively, you can import the file directly to the Power BI service and create a dashboard from there.

## Contact Me

If you have any questions, feedback, or suggestions for this dashboard, please feel free to contact me. You can also check out my other Power BI projects on my GitHub profile. Thank you for your interest and support!
