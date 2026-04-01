# Diwali_Sales_Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Diwali sales data to understand customer behavior, sales trends, and product performance during the festive season.

The analysis is done using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.


## 🎯 Objectives

* Clean and preprocess raw sales data
* Analyze customer demographics (Gender, Age, Marital Status, Occupation)
* Identify top-performing states and product categories
* Visualize insights using graphs and charts


## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Basic plotting
* **Seaborn** – Advanced data visualization


## 📂 Dataset Information

The dataset contains sales-related attributes such as:

* User ID
* Gender
* Age Group
* State
* Marital Status
* Occupation
* Product Category
* Product ID
* Orders
* Amount

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

* Removed unnecessary columns (`Status`, `unnamed1`)
* Checked and removed null values
* Converted `Amount` column to integer type
* Renamed columns where required
* Verified dataset using `.info()` and `.describe()`


## 📊 Exploratory Data Analysis (EDA)

### 👩 Gender Analysis

* Created count plots for Gender distribution
* Compared total purchase amount by Gender

👉 **Insight:**
Females are the majority buyers and have higher purchasing power than males.


### 🎂 Age Group Analysis

* Count plot of Age Group vs Gender
* Total sales by Age Group

👉 **Insight:**
Customers aged **26–35 years (especially females)** contribute the most to sales.

### 💼 Occupation Analysis

* Count plot of occupation distribution
* Sales by occupation

👉 **Insight:**
Top contributing sectors:

* IT
* Healthcare
* Aviation

👉 **Insight:**
Most popular categories:

* Food
* Clothing
* Electronics


### 🏆 Top Products Analysis

* Top 10 most sold products (based on orders)
* Bar chart visualization of product demand

👉 **Insight:**
A few products dominate overall sales volume.

## 📈 Key Insights Summary

* Females (especially married) are the primary buyers
* Age group **26–35 years** drives maximum sales
* Top states: **Uttar Pradesh, Maharashtra, Karnataka**
* High-performing sectors: **IT, Healthcare, Aviation**
* Best-selling categories: **Food, Clothing, Electronics**


## 💡 Future Enhancements

* Build an interactive dashboard (Power BI / Tableau)
* Apply machine learning for sales prediction
* Automate insights generation

## 🙌 Conclusion

This analysis helps businesses understand **customer segmentation and product demand**, enabling better marketing strategies and improved sales performance during festive seasons.
