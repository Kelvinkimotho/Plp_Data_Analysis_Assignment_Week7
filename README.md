# 🛍️ Supermarket Sales Data Analysis & Visualization

## Overview

This notebook provides a comprehensive analysis of the **Supermarket Sales Dataset**, which records transaction data from a retail supermarket chain across three major cities in Myanmar: **Yangon**, **Naypyitaw**, and **Mandalay**. The data spans the first quarter of 2019 and includes detailed customer, sales, and product information.

This dataset is ideal for exploring patterns in **sales behavior**, **customer demographics**, and **transaction trends**. It includes variables such as product line, customer type, payment method, sales amount, rating, and more.

---

## Dataset Features

The dataset includes **1000 rows** and **17 columns**:

- **Invoice ID**: Unique transaction identifier  
- **Branch**: Branch code (e.g., A, B, C)  
- **City**: City location of the branch  
- **Customer Type**: Member or Normal  
- **Gender**: Customer gender  
- **Product Line**: Category of product purchased  
- **Unit Price**: Price per unit  
- **Quantity**: Number of units purchased  
- **Tax 5%**: 5% tax on total  
- **Total**: Total cost (including tax)  
- **Date**: Date of purchase  
- **Time**: Time of purchase  
- **Payment**: Payment method used  
- **COGS**: Cost of goods sold  
- **Gross Margin %**: Fixed margin percentage  
- **Gross Income**: Profit from transaction  
- **Rating**: Customer satisfaction score (1–10)

---

## Objectives

The main objectives of this notebook are to:

1. **Load and Clean the Dataset**
   - Load the CSV file using pandas
   - Convert and extract useful date/time information
   - Check for missing or duplicate values

2. **Perform Basic Data Analysis**
   - Compute summary statistics
   - Group and compare key metrics by categories (e.g., product line, gender)
   - Derive meaningful business insights

3. **Visualize the Data**
   - Generate a variety of charts using `matplotlib` and `seaborn`:
     - Line chart: Sales over time
     - Bar chart: Average sales by product line
     - Histogram: Distribution of customer ratings
     - Scatter plot: Quantity vs. total sales
     - Pie chart: Payment method usage
     - Box plot: Sales spread by branch
     - Additional visuals: Sales by weekday

4. **Save All Visualizations as Images**
   - Each plot will be saved in the `plots/` directory for easy reference or report creation

---

## Tools & Libraries

- **pandas** for data handling and manipulation  
- **matplotlib** and **seaborn** for high-quality visualizations  
- **NumPy** for numerical operations

---

Let’s dive into the data and uncover trends that can support strategic business decisions! 
