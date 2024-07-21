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
 3. Exploratory Analysis: Perform univariate, bivariate, multivariate analysis, correlation and causation.
 4. Visualization: Use matplotlib and plotly for data visualization.
 5. Insights: Summarize key findings and insights.

**Project Structure**

![image](https://github.com/user-attachments/assets/0813900f-d33a-4596-87d2-5bb23cffc6bf)


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

1. Items Sold By Country/Seasonality: Our plots indicated that there is not a significant seasonal trend in sales data but there are definitely geographic trends.
2. Top Product Categories by Country: Women's shoes and women's clothing were the top categories.
3. Top Products Sold By Category in Italy and USA: Our analysis shows that women's clothing was the top category from Italy while Women's shoes was the top category in the USA. 
4. Gender Distribution of Buyers: Pie charts revealed the gender distribution of buyers with about 60% of buyers being women.
5. Seller Location By Country: Bubble maps displayed the geographical distribution of sellers, highlighting key markets which are concentrated in Europe.
6. Top Selling Brands: Top selling brands include Gucci, Prada, Hermes.
7. Material: Pie charts illustrated the seasonality of material sales, indicating material preferences during different seasons.
8. Price/Margin Analysis: Detailed analysis on price and margin provided insights into profitability.
9. Brand Condition: Never worn with tag, never worn were the top sellers.

These insights can help in optimizing marketing strategies, inventory management, and overall business planning.

## Contributors

Lucas Heuer - https://github.com/lucheuer

Rebecca Storer - https://github.com/ReccaS

Natalie Brewer - https://github.com/nbrew3000

Michael Sheveland - https://github.com/MichaelSheveland

Russell Haskell - https://github.com/rhask87062

## License
Public
