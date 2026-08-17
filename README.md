# House Sales King County Analysis

## 📊 Project Overview

Analysis of residential property sales in King County, Seattle, using an interactive Excel dashboard and exploratory data analysis in Python.

The project focuses on understanding housing prices and identifying the main characteristics associated with differences in property value.

## 🎯 Objectives

* Clean and validate the original housing dataset.
* Analyze the distribution of property prices.
* Explore the relationship between price and housing characteristics.
* Identify relevant patterns by city, bedrooms, bathrooms, living area and waterfront.
* Build an interactive Excel dashboard with PivotTables, charts and slicers.

## 🧹 Data Cleaning

The original dataset contained **4,600 properties and 18 variables**.

During the cleaning process, recording errors and anomalous observations were reviewed. After cleaning:

* **4,354 properties** remain.
* **0 null values**.
* **0 duplicate records**.
* No properties with `price = 0`.
* No properties with both `bedrooms = 0` and `bathrooms = 0`.

## 📈 Key Findings

* The **average house price** is **$547,179.57**, while the **median price** is **$462,000**, indicating a distribution influenced by higher-priced properties.
* **Mercer Island** has the highest average price among cities with at least 30 properties, followed by **Bellevue** and **Sammamish**.
* Average price generally increases as the number of **bedrooms** increases, although the relationship is not perfectly linear.
* Properties with **waterfront access** have a substantially higher average price than properties without waterfront access.
* Living area (`sqft_living`) shows a strong positive relationship with house price.

## 📊 Interactive Dashboard

The Excel dashboard allows users to explore the data dynamically using slicers and charts.

The dashboard includes:

* Number of properties
* Average price
* Median price
* Median price per square foot
* Average price by city
* Average price by number of bedrooms
* Average price by bathrooms
* Average price by living area
* Average price by waterfront status
* Interactive slicers for filtering the analysis

When a slicer is cleared, the dashboard returns to the complete dataset, allowing the user to explore different combinations of filters.

## 🛠️ Tools Used

* **Python** — data cleaning and exploratory analysis
* **Pandas** — data manipulation
* **Jupyter Notebook** — analysis workflow
* **Microsoft Excel** — PivotTables, charts, slicers and interactive dashboard

## 📁 Repository Contents

* `House_Sales_King_County_EDA.ipynb` — Python exploratory data analysis and data cleaning.
* `House_Sales_King_County_Dashboard.xlsx` — interactive Excel dashboard.
* `Housing_Market_Analysis_Report.pdf` — project report with the main analysis and conclusions.

## 👩‍💻 Author

**María del Mar Jaén**
