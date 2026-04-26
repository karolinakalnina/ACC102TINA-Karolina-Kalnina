# ACC102TINA-Karolina-Kalnina
# Global Sports Footwear Sales Analysis

## Overview
This project analyses the **Global Sports Footwear Sales** dataset to explore purchasing patterns, sales performance, customer behaviour, and brand trends across different categories, genders, income levels, and sales channels.

The main goal of this project is to identify meaningful insights from sales data that can help better understand:
- which brands and categories perform best,
- how purchasing behaviour differs across genders,
- how income level may relate to purchasing patterns,
- how sales channels affect revenue, pricing, and units sold,
- and what overall trends appear in the dataset.

## Problem Statement
Sports footwear companies and retailers need to understand customer purchasing behaviour in order to improve pricing strategies, product positioning, sales channel performance, and inventory planning.

This project addresses the problem of turning raw footwear sales data into clear, visual insights that support better business understanding and decision-making.

## Intended Users of the Dataset
This dataset and analysis may be useful for:
- business analysts
- retail managers
- marketing teams
- data analysts and students
- researchers interested in consumer behaviour
- anyone exploring sports footwear market trends

Users can use this data to identify customer buying patterns, compare sales performance across groups, and support business decisions using evidence from the dataset. It can also be used for learning, exploratory data analysis practice, and creating visualisations to better understand sports footwear sales trends.

## Dataset
The dataset used in this project is:

`global_sports_footwear_sales_2018_2026.csv`

This file is included in the GitHub repository.

### Dataset Source
- **Source:** Kaggle
- **Access Date:** 19 of April 

### How to Use the Data
To use the dataset:
1. Download or clone this GitHub repository.
2. Make sure the file `global_sports_footwear_sales_2018_2026.csv` is saved in the same working directory as the notebook or Python script.
3. Load the dataset into Python using pandas for analysis and visualisation.

## Key Variables Used in the Notebook
The main variables used in this analysis are:

- `brand` — footwear brand name
- `category` — product category
- `gender` — target gender group
- `income_level` — customer income group
- `sales_channel` — sales channel used for the purchase
- `revenue_usd` — revenue generated from sales
- `final_price_usd` — final selling price
- `units_sold` — number of units sold

These variables were used to compare purchasing behaviour and sales performance across multiple groups.

## How to Run the Project
The workflow used in this project is:

1. Import Python libraries
2. Load the dataset
3. Inspect the structure of the data
4. Check data types and missing values
5. Clean the data where needed
6. Generate descriptive statistics
7. Explore patterns by brand, category, gender, income level, and sales channel
8. Create visualisations such as bar charts and count plots
9. Interpret the results
10. Summarise findings, limitations, and possible improvements

## Python Libraries Used
The main Python libraries used in this project are:

- `pandas` — for data loading and manipulation
- `NumPy` — for numerical operations
- `matplotlib` — for visualisations
- `seaborn` — for statistical graphics and chart styling

## Key Findings
Some of the main findings from the notebook include:

- Brand purchase proportions were broadly similar across gender groups, with only small differences between men, women, and unisex products.
- Sales channel comparisons showed variation in average revenue, average final price, and average units sold.
- Category purchases differed by gender, which could be seen clearly in grouped count plots.
- Income level comparisons provided additional context for customer purchasing behaviour.
- Visual analysis helped highlight which brands and categories contributed most to purchasing patterns.

## Limitations
This project has several limitations:

- The analysis depends on the quality and completeness of the dataset.
- The results are mainly based on descriptive analysis and visualisations.
- Observed patterns do not necessarily show causation.
- Some useful context may be missing, such as location, time trends, promotions, or customer-specific behaviour.
- If the dataset is simulated or cleaned before publication, real-world conclusions should be made carefully.

## Possible Improvements
This project could be improved further by:

- adding more advanced statistical analysis
- investigating trends over time
- including region or country-level comparisons
- building predictive models for forecasting sales
- creating interactive dashboards
- exploring more relationships between variables
- applying feature engineering for deeper insights

## Repository Contents
This repository includes:

- `global_sports_footwear_sales_2018_2026.csv` — the dataset used for analysis
- notebook or Python script file(s) containing the analysis
- `README.md` — project description and documentation
  

## Author
Tina Karolina Kalnina
