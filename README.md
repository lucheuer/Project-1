## Project-1-Group 3: E-commerce Exploratory Data Analysis
Welcome to the E-commerce Exploratory Data Analysis project! This project aims to analyze e-commerce data to uncover insights and trends. This README file provides detailed instructions on how to install and use this project.
## Table of Contents
* Installation
* Usage
* Project Structure
* Examples
* Summary of Analysis
* Contributing
* License
## Installation
**Prerequisites**

Before you begin, ensure you have met the following requirements:

Python 3.8 or higher

pip (Python package installer)

**Create and Clone the repository**

* Create a new repository for this project called Project-1. 
* Clone the Repository
  * git clone https://github.com/lucheuer/Project-1.git
  * cd Project-1
* Inside your local Git repository, add the datafile files from your file downloads.
* Push these changes to GitHub or GitLab.

**Install Dependencies**

Install the required packages using pip:
* import pandas as pd
* import matplotlib.pyplot as plt
* import numpy as np
* import plotly.graph_objects as go
* import plotly.colors as pc

## Usage

**Jupyter Notebook**

The analysis is performed using Jupyter Notebook. To start Jupyter Notebook, run:
* jupyter notebook
  * Open the notebook 'project-1.ipynb

 **Example Analysis**

 Here's a brief overview of how to run the exploratory data analysis:

 1. Load Data: Load the e-commerce dataset into a DataFrame.
 2. Data Cleaning: Handle missing values, data types, and duplicates.
 3. Exploratory Analysis: Perform univariate, bivariate, and multivariate analysis.
 4. Visualization: Use matplotlib and plotly for data visualization.
 5. Insights: Summarize key findings and insights.

**Project Structure**

project-1/ 
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── scripts/
│   ├── data_cleaning.py
│   ├── data_visualization.py
│   └── exploratory_analysis.py
│
├── examples/
│   ├── items_sold_by_country_seasonality.png
│   ├── top_product_categories_by_country.png
│   ├── top_products_sold_by_category_italy.png
│   ├── top_products_sold_by_category_usa.png
│   ├── top_countries_by_total_earnings.png
│   ├── gender_distribution_of_buyers.png
│   ├── seller_location_by_country.png
│   ├── top_selling_brands.png
│   ├── condition_of_items_by_brand.png
│   ├── seasonality_material.png
│   └── key_findings.md
│
├── requirements.txt
├── README.md

* data/: Contains raw and processed data files.
* notebooks/: Jupyter Notebooks for analysis.
* scripts/: Python scripts for various stages of the analysis.
* examples/: Examples of analysis results and key findings.
* requirements.txt: Lists the Python packages required for the project.
* README.md: Project documentation.

**Examples**

Items Sold By Country/Seasonality

Top 20 Product Categories by Country

Top Products Sold By Category in Italy

Top Products Sold By Category in USA

Top 10 Countries by Total Earnings (Products Sold)

Gender Distribution of Buyers

Seller Location By Country

Top Selling Brands

Condition of Items By Brand

Seasonality/Material

**Summary of Analysis**

The exploratory data analysis of the e-commerce dataset revealed several key insights:

1. Items Sold By Country/Seasonality: Scatter plots indicated significant seasonal trends in sales across various countries.
2. Top Product Categories by Country: Bar graphs highlighted the top 20 product categories in different countries, showing regional preferences.
3. Top Products Sold By Category in Italy and USA: Bar graphs identified the most popular products in Italy and the USA, showcasing consumer preferences.
4. Top 10 Countries by Total Earnings: Bar graphs illustrated the countries with the highest total earnings from product sales.
5. Gender Distribution of Buyers: Pie charts revealed the gender distribution of buyers, providing insights into the target audience.
6. Seller Location By Country: Bubble maps displayed the geographical distribution of sellers, highlighting key markets.
7. Top Selling Brands: Line graphs tracked the performance of top-selling brands over time.
8. Condition of Items By Brand: Bar graphs analyzed the condition of items sold by different brands, showing quality trends.
9. Seasonality/Material: Pie charts illustrated the seasonality of material sales, indicating material preferences during different seasons.
10. Price/Margin Analysis: Detailed analysis on price and margin provided insights into profitability.

These insights can help in optimizing marketing strategies, inventory management, and overall business planning.

## Contributors

Lucas Heuer - https://github.com/lucheuer

Rebecca Storer - https://github.com/ReccaS

Natalie Brewer - https://github.com/nbrew3000

Michael Sheveland - https://github.com/MichaelSheveland

Russell Haskell - 

## License
Public















