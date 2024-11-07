# **Revenue Increase Analysis of Maven Toys 🧸**

Revenue increase analysis of Maven Toys Stores in Mexico for Q4 2018 using Python and Tableau.

## **Introduction 🧑‍💼**

Maven Toys is a prominent toy store located in Mexico. As of the end of Q3 2018, the store has encountered a decline in revenue compared to the previous quarter. To address this challenge, Maven Toys is striving to increase its revenue by the end of Q4. An in-depth analysis of sales data from January 1, 2017, to September 30, 2018, is underway, focusing on identifying potential revenue growth opportunities for Q4 2018.

## **Data Overview 📊**

This dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/toy-sales/data) and comprises over 829,262 transactions across all stores operated by Maven Toys, providing a robust foundation for analysis.

The dataset includes four tables, each containing essential information as follows:

### **Inventory Table 🏬**

| No | Column Name      | Description | Range/Value |
|----|------------------|-------------|-------------|
| 1  | Store_ID         | Store ID    | Unique identifier for each store (PK) |
| 2  | Product_ID       | Product ID  | Unique identifier for each product (FK) |
| 3  | Stock_On_Hand    | Quantity of product in stock (inventory) | Integer value representing stock quantity |

### **Product Table 🛍️**

| No | Column Name      | Description | Range/Value |
|----|------------------|-------------|-------------|
| 1  | Product_ID       | Product ID  | Unique identifier for each product (PK) |
| 2  | Product_Name     | Product Name| Name of the product |
| 3  | Product_Category | Product Category | Category to which the product belongs |
| 4  | Product_Cost     | Product Cost ($USD) | Decimal value representing product cost |
| 5  | Product_Price    | Retail Price of Product ($USD) | Decimal value representing retail price |

### **Sales Table 💰**

| No | Column Name      | Description | Range/Value |
|----|------------------|-------------|-------------|
| 1  | Sale_ID          | Sale ID     | Unique identifier for each sale (PK) |
| 2  | Date             | Transaction Date | Date when the sale occurred |
| 3  | Store_ID         | Store ID    | Unique identifier for each store (FK) |
| 4  | Product_ID       | Product ID  | Unique identifier for each product (FK) |
| 5  | Units            | Number of Units Sold | Integer value representing the number sold |

### **Stores Table 🏪**

| No | Column Name      | Description | Range/Value |
|----|------------------|-------------|-------------|
| 1  | Store_ID         | Store ID    | Unique identifier for each store (PK) |
| 2  | Store_Name       | Store Name  | Name of the store |
| 3  | Store_City       | City in Mexico where the store is located | Name of the city |
| 4  | Store_Location   | Location within the city where the store is found | Specific location within the city |
| 5  | Store_Open_Date  | Date when the store opened | Date of the store's opening |

## **Objectives 🎯**

The main objectives of this analysis are:

- To assess the revenue performance of Maven Toys from Q3 2017 to Q4 2018.
- To identify key factors influencing revenue changes.
- To provide actionable recommendations for revenue growth in Q4 2018 and beyond.

## Methodology 🔍

The analysis consists of the following steps:

1. **Data Cleaning and Preprocessing**: Handling missing values, correcting data types, and preparing data for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding key patterns, trends, and outliers.
3. **Data Visualization**: Using Tableau for creating interactive visualizations to represent key findings.
4. **Statistical Analysis**: Calculating correlations, performing hypothesis testing, and identifying trends in the data.

## **Conclusion 📈**

Toy sales experienced a significant spike in Q4. **The 35% revenue increase target in Q4 2018 is achievable** if **Maven Toys optimizes efficient sales strategies**, including **inventory management** and **appropriate promotions**.

## **Recommendations 💡**

Based on the analysis, there is a strong indication that achieving a 35% revenue increase in Q4 2018 is feasible. Seasonal patterns and success in specific product categories provide opportunities to further drive sales. To achieve this target, the recommended strategies include:

1. **Create Bundles** 🎁: Combine best-selling products with slower-moving items in bundles to increase the appeal of less popular products.

2. **Product Bundle Packages** 🎉: Offer attractive product bundles to encourage customers to purchase more items at once, increasing overall sales volume.

3. **Segmented Discounts** 💸: Apply targeted discounts on top-selling products during high-sales periods, such as December 24th and 31st, in high-performing locations. For lower-performing locations, offer smaller discounts to attract sales without sacrificing too much margin.

4. **Optimize Inventory** 📦: Monitor stock levels in real-time. Increase stock for high-demand products and ensure quick restocking to prevent product shortages.

5. **Targeted Marketing Campaigns** 📣: Launch marketing campaigns based on consumer buying patterns, especially for bulk-purchase-prone product categories, to maximize customer engagement and boost sales during peak seasons.

6. **Loyalty Programs** 🏅: Offer loyalty rewards for customers purchasing in bulk or purchasing from high-demand categories, encouraging repeat business and larger purchases.

7. **Seasonal Promotions** 🎄: Plan for seasonal promotions that capitalize on high-purchase periods, aligning discounts and offers with customer shopping behaviors during peak months.

By implementing these strategies, it is expected that Maven Toys can reach the 35% revenue target in Q4 2018.

## **Link Tableau 📊**

You can explore the interactive visualizations and insights in Tableau at the following link:  
[Tableau Dashboard: Maven Toys Revenue Analysis](https://public.tableau.com/app/profile/karen.lontoh/viz/MavenToys_17273574900020/Summary?publish=yes)

## **Dependencies 📚**

- Python 3.12.4
- Tableau

### **Libraries 🛠️**

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## **Author 👩‍💻**

Karen Lontoh  
[![LinkedIn](https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png)](https://www.linkedin.com/in/karmenia-lontoh) Karen Lontoh
