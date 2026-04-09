# Washington Real Estate Market Analysis (EDA)

## Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the *Washington Real Estate: Sold Properties 2026* dataset.
The goal is to explore housing market trends, understand property characteristics, and identify factors that influence house prices.

Through data cleaning, visualization, and analysis, this project investigates relationships between variables such as property size, number of bedrooms, bathrooms, and sale prices.

---

## Dataset Information

The dataset contains **12,000+ real estate transactions** with information about property characteristics and sale details.

### Main Features

| Column             | Description                                |
| ------------------ | ------------------------------------------ |
| zip                | ZIP code of the property                   |
| type               | Property type (house, condo, etc.)         |
| year_built         | Year the property was built                |
| listPrice          | Listing price of the property              |
| lastSoldPrice      | Final sold price                           |
| list_to_sold_ratio | Ratio between listing price and sold price |
| sqft               | Property size in square feet               |
| price_per_sqft     | Price per square foot                      |
| stories            | Number of floors                           |
| beds               | Number of bedrooms                         |
| baths              | Number of bathrooms                        |
| baths_full         | Number of full bathrooms                   |
| baths_full_calc    | Calculated full bathrooms                  |
| garage             | Garage availability                        |
| sanitized_text     | Property description text                  |

---

## Project Steps

### 1. Data Cleaning

* Removed columns with excessive missing values.
* Handled missing values using median imputation.
* Converted data types when necessary.

### 2. Exploratory Data Analysis

The dataset was analyzed to answer several key questions:

* What is the distribution of house prices?
* How does house size affect property prices?
* Do more bedrooms increase house value?
* How does property type affect price?
* Are newer houses more expensive?

### 3. Feature Engineering

A new feature was created:

* **House Age** = Current Year − Year Built

This helps analyze how the age of a property influences price.

### 4. Text Analysis

Property descriptions were analyzed using **WordCloud** to identify the most frequent terms used in listings.

---

## Data Visualization

The following visualizations were created during the analysis:

* House price distribution
* House size vs sale price
* Bedrooms vs price
* Property type vs price
* Price per square foot distribution
* Correlation heatmap
* Year built vs sale price
* Word cloud of property descriptions

---

## Key Insights

Some interesting findings from the analysis:

* Larger houses tend to have higher selling prices.
* Properties with more bedrooms and bathrooms generally sell for more.
* Price per square foot varies significantly across properties.
* Newer houses tend to have higher market values.
* Property descriptions often emphasize features such as location, modern design, and spacious layouts.

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **WordCloud**
* **Jupyter Notebook**


---

## Author

Gizem Sena Çengel
Data Analysis & Machine Learning Projects
