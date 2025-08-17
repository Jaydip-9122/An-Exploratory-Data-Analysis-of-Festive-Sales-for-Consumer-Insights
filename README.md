# Diwali Sales Data Analysis

## Project Overview

This project performs an in-depth exploratory data analysis (EDA) on Diwali sales data to uncover key trends and insights. The goal is to understand customer behavior and identify the primary drivers of sales during the Diwali season. By analyzing various customer demographics and product categories, the project provides actionable insights that can help guide business and marketing strategies.

## Dataset

The analysis uses the `Diwali Sales Data.csv` dataset. This dataset contains 11,251 rows of transactional data, with columns detailing customer information and purchase details.

**Columns include:**

* `User_ID`, `Cust_name`

* `Product_ID`, `Product_Category`

* `Gender`, `Age Group`, `Age`, `Marital_Status`

* `State`, `Zone`, `Occupation`

* `Orders`, `Amount`

## Analysis Steps

The analysis was conducted in a Jupyter Notebook (`CODE.ipynb`) and followed these key steps:

### 1. Data Cleaning

* **Import Libraries:** Imported essential Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.

* **Load Data:** The dataset was loaded into a Pandas DataFrame.

* **Handle Missing Data:**

  * Identified and removed columns with no data (`Status`, `unnamed1`).

  * Checked for and dropped rows containing null values.

* **Data Type Conversion:** Changed the `Amount` column from a float to an integer data type for consistency.

### 2. Exploratory Data Analysis (EDA)

A detailed analysis was performed to understand sales patterns based on different attributes:

* **Gender:** Analyzed the distribution of buyers and their purchasing power by gender.

* **Age:** Investigated sales distribution across different age groups, segmented by gender.

* **State:** Identified the top 10 states by total orders and sales amount.

* **Marital Status:** Examined the purchasing behavior of married vs. unmarried customers.

* **Occupation:** Determined which professional sectors contributed most to sales.

* **Product Category:** Analyzed the most popular product categories by sales and number of orders.

* **Product ID:** Identified the top 10 best-selling products.

## Key Insights & Findings

* **Gender:** Women are the primary buyers and have significantly higher purchasing power than men.

* **Age:** The 26-35 age group accounts for the highest number of sales, with females being the dominant shoppers in this segment.

* **Location:** Uttar Pradesh, Maharashtra, and Karnataka are the top three states in terms of both the number of orders and total sales amount.

* **Marital Status:** Married women constitute the largest segment of buyers and have the highest purchasing power.

* **Occupation:** Customers working in IT, Healthcare, and Aviation are the top three spenders.

* **Product Category:** The most profitable product categories are **Food**, **Clothing & Apparel**, and **Electronics & Gadgets**.

## Conclusion

The analysis reveals a clear target customer profile for Diwali sales: **married women between the ages of 26-35, residing in Uttar Pradesh, Maharashtra, or Karnataka, and working in the IT, Healthcare, or Aviation sectors.** This demographic is most likely to purchase products from the **Food, Clothing, and Electronics** categories.

These insights can be leveraged to create targeted advertising campaigns, manage inventory, and customize promotions to maximize sales in the future.

## Tools and Libraries Used

* **Python 3**

* **Pandas:** For data manipulation and analysis.

* **NumPy:** For numerical operations.

* **Matplotlib & Seaborn:** For data visualization.

* **Jupyter Notebook:** As the development environment.

## How to Run This Project

1. **Prerequisites:**

   * Python 3 installed.

   * Jupyter Notebook installed.

2. **Installation:**
   Install the required libraries using pip:

pip install pandas numpy matplotlib seaborn jupyter
3. **Execution:**

* Download or clone the project files, including `CODE.ipynb` and `Diwali Sales Data.csv`.

* Place the CSV file in the same directory as the notebook.

* Launch Jupyter Notebook:

  ```
  jupyter notebook
  
  ```

* Open `CODE.ipynb` and run the cells sequentially to reproduce the analysis.
