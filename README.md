Welcome to the Superstore Sales Analysis & Forecasting project! This repository contains a Power BI report with visualizations based on Superstore sales data from 2020 to 2023. The project is divided into two main pages: Sales Dashboard and Sales Forecasting.

## Project Overview

### Sales Dashboard

The Sales Dashboard is designed to provide an in-depth analysis of sales data, focusing on various factors that influence sales performance. Key features include:

- **KPIs:** 
  - Total Sales
  - Total Quantity of Products
  - Total Profit
  - Average Delivery Time

- **Visualizations:**
  - **Stacked Area Charts:** Compare sales and profit across different years.
  - **Category Analysis:** Breakdown of sales by category and sub-category.
  - **Geographical Analysis:** Sales performance across different regions.
  - **Shipping Analysis:** Impact of different ship modes on sales.
  - **Segment Analysis:** Sales distribution across various customer segments.

### Sales Forecasting

The Sales Forecasting page utilizes time series analysis techniques to forecast future sales trends. This includes:

- **Time Series Decomposition:** Breaking down the sales data into trend, seasonal, and residual components.
- **Forecast Models:** Applying predictive models to provide accurate sales forecasts.

## Getting Started

### Prerequisites

- **Power BI Desktop:** Ensure you have the latest version of Power BI Desktop installed on your machine.
- **Superstore Sales Data:** Ensure you have the `superstore_sales.csv` file containing the sales data from 2020 to 2023.
  
### Steps to Create the Sales Dashboard
1. **Load the Data:**
   - Open Power BI Desktop.
   - Click on `Get Data` and select `Text/CSV`.
   - Navigate to the location of the `Superstore 2023.csv` file and load it into Power BI.

2. **Data Cleaning and Transformation:**
   - Go to the `Transform Data` option to open the Power Query Editor.
   - Check for any missing or inconsistent data and clean it as needed. Especially the date fields had a mix of mm/dd/yyyy and dd/mm/yyyy format entries. So I did the data transformation using M- Query to fix the data error.
   - Ensure data types are correctly set (e.g., dates as Date type, sales as Currency type).

3. **Create Relationships (if necessary):**
   - Here there was only one dataset. So, no relationships were created.

4. **Design the Sales Dashboard:**
   - **KPIs:** 
     - Use `Card` visualizations to display Total Sales, Total Quantity of Products, Total Profit, and Average Delivery Time.
   - **Stacked Area Charts:**
     - Created `Stacked Area Charts` to compare Sales and Profit year-over-year.
   - **Category Analysis:**
     - Used `Clustered Bar Charts` to show sales breakdown by Category and Sub-Category.
   - **Geographical Analysis:**
     - Used `Map` visualizations to display sales performance across different regions.
   - **Shipping Analysis:**
     - Created `Bar Charts` to analyze the impact of different Ship Modes on sales.
   - **Segment Analysis:**
     - Used `Donut Charts` to display sales distribution across various Customer Segments.

5. **Create the Sales Forecasting Page:**
   - Used `Line Charts` to visualize and analyze sales trends.
   - Applied `Forecasting` features available in Power BI to predict future sales.

6. **Finalize and Publish:**
   - Reviewed and finalized the dashboard layout and visualizations.
   - Saved the Power BI report file as `Retail Store Sales Dashboard.pbix`and uploaded to the repository.

### Snapshots of the report screens with visuals mentioned earlier
1. **Sales Dashboard**
   
