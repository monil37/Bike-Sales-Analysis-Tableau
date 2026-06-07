# Bike Sales Analysis using Tableau

## Project Overview
This project features an interactive Tableau dashboard built to analyze global bike sales. It breaks down performance metrics by region, customer demographics, and product categories. By visualizing key data like revenue trends and purchasing behavior, this dashboard provides clear insights to help businesses make data-driven decisions.

## Final Sales Dashboard
![Bike Sales Dashboard](Sales%20Dashboard.png)

## Key Features & Visualizations
The dashboard is fully interactive, utilizing **Country** and **Year** parameters to allow users to filter and drill down into the data dynamically. Key components include:

- **KPI Cards**: High-level metrics showcasing Total Profit, Year-over-Year (YoY) % Change, Total Revenue (with a trend line), and Cost by Product Category (Accessories, Bikes, Clothing).
- **Top 10 Product Sales by Order Quantity**: A horizontal bar chart highlighting top-moving items like Water Bottles, Patch Kits, and Tire Tubes.
- **Product Category Sales by Gender**: A stacked bar chart comparing profitability and sales performance across product categories, split by Male and Female demographics.
- **Sales by Age Group and Product Sub-category**: A packed bubble chart illustrating sales distribution across age demographics (Youth, Young Adults, Adults, Seniors).
- **Sales by Country**: A geographic map detailing sales density across major operating regions (Australia, Canada, France, Germany, United Kingdom, United States).

## Dataset (Sales.xlsx)
Below is a breakdown of the core columns available in the dataset used to build the dashboard:

| Column Name | Description |
| :--- | :--- |
| **Date / Year** | The date and year the transaction occurred (used for dynamic time-period filtering). |
| **Customer Age** | The age of the purchasing customer. |
| **Age Group** | Categorized demographic group of the customer (Youth, Young Adults, Adults, Seniors). |
| **Customer Gender** | The gender of the customer (Male, Female). |
| **Country** | The geographical country where the sale was made (e.g., Australia, Canada, US). |
| **State / Region** | The geographical state or province of the transaction. |
| **Product Category** | The broad classification of the product (Accessories, Bikes, Clothing). |
| **Sub-Category** | The detailed grouping of products (e.g., Water Bottles, Patch Kits, Tire Tubes). |
| **Product** | The specific name of the item purchased. |
| **Order Quantity** | The total number of units bought in a single transaction. |
| **Unit Cost** | The base cost to manufacture or acquire one unit of the item. |
| **Unit Price** | The standard selling price per unit. |
| **Revenue** | Total revenue generated from the transaction. |
| **Cost** | Total cost associated with the transaction. |
| **Profit** | The net profit realized from the sale (Revenue - Cost). |

## Tasks Performed
- **Data Connection & Preparation**: Connected the raw dataset (**Sales.xlsx**) to Tableau, ensuring appropriate data types and geographic roles were accurately established before analysis.
- **Calculated Fields**: Developed custom formulas to extract specific Key Performance Indicators (KPIs), notably the Year-over-Year (YoY) percentage change for dynamic time-period comparisons.
- **Visualization Design**: Built distinct, effective visualizations (geospatial maps, bar charts, line graphs, and packed bubbles) best suited to represent the underlying data accurately.
- **Dashboard Layout & UI**: Assembled the individual worksheets into a single, cohesive dashboard. Applied consistent formatting, custom shading, and organized containers for a polished user experience.


## Tools Used
- **Tableau Desktop**: For data visualization, dashboarding, and interactive analytics.


**Thank you and happy learning!**