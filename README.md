---

# Retail Performance Dashboard – Overview & Insights

## Overview

This **Retail Performance Dashboard** built in Excel is designed to provide a comprehensive and dynamic analysis of retail business metrics. Using key datasets like **Orders**, **Returns**, and **People**, the dashboard visually represents important KPIs, trends, and problem-solving insights for improved business decision-making. The data has been processed and visualized to provide actionable insights into areas like sales performance, returns analysis, and employee performance.
---

## Sample Data Tables

### **Orders Table**
| Order ID         | Order Date | Ship Date  | Ship Mode    | Customer Name | Segment   | Country      | Sales   | Profit  | Quantity | Discount |
|------------------|------------|------------|--------------|---------------|-----------|--------------|---------|---------|----------|----------|
| CA-2012-124891   | 31-07-2020 | 31-07-2020 | Same Day     | Rick Hansen   | Consumer  | United States| 2309.65 | 762.18  | 7        | 0        |
| IN-2013-77878    | 05-02-2021 | 07-02-2021 | Second Class | Justin Ritter | Corporate | Australia    | 3709.40 | -288.77 | 9        | 0.1      |
| IN-2013-71249    | 17-10-2021 | 18-10-2021 | First Class  | Craig Reiter  | Consumer  | Australia    | 5175.17 | 919.97  | 9        | 0.1      |
| ES-2013-1579342  | 28-01-2021 | 30-01-2021 | First Class  | Katherine Murray | Home Office | Germany    | 2892.51 | -96.54  | 5        | 0.1      |
| SG-2013-4320     | 05-11-2021 | 06-11-2021 | Same Day     | Rick Hansen   | Consumer  | Senegal      | 2832.96 | 311.52  | 8        | 0        |

### **Return Table**
| Returned | Order ID         | Market     |
|----------|------------------|------------|
| Yes      | MX-2013-168137   | LATAM      |
| Yes      | US-2011-165316   | LATAM      |
| Yes      | ES-2013-1525878  | EU         |
| Yes      | CA-2013-118311   | United States |
| Yes      | ES-2011-1276768  | EU         |

### **People Table**
| Person            | Region  |
|-------------------|---------|
| Anna Andreadi     | Central |
| Chuck Magee       | South   |
| Kelly Williams    | East    |
| Matt Collister    | West    |
| Deborah Brumfield | Africa  |

---

## KPI Table

The KPI table consolidates the most essential performance metrics for the retail analysis. These KPIs allow the dashboard to provide actionable insights by comparing important aspects of sales performance.

| KPI Name          | Symbol | Formula                         |
|-------------------|--------|---------------------------------|
| Total Sales       | 💰     | SUM(Sales)                      |
| Total Profit      | 📈     | SUM(Profit)                     |
| Total Quantity    | 📦     | SUM(Quantity)                   |
| No of Orders      | 🛒     | COUNT(Order ID)                 |
| Profitability     | 🔍     | SUM(Profit) / SUM(Sales)        |

---

Each visualization in the dashboard corresponds to a specific business problem statement, offering a clear view of performance across multiple dimensions.

---

## Datasets Analyzed

### 1. **Orders Dataset**

The **Orders** dataset provides detailed records of all retail transactions. It includes key information such as order ID, sales, profit, product category, shipping details, and customer information. This dataset is crucial for calculating sales, profit, shipping costs, and other important business KPIs.

**Key Columns**:

* **Order ID**: Unique identifier for each order
* **Sales**: Total sales value per order
* **Profit**: Profit earned from the order
* **Category**: Product category of the ordered item
* **Shipping Cost**: Cost of shipping the order

---

### 2. **Returns Dataset**

The **Returns** dataset tracks which orders were returned, along with the market region. This dataset helps in analyzing the impact of returns on the overall performance, revealing trends or patterns that could be important for operational improvements.

**Key Columns**:

* **Returned**: Whether the order was returned or not
* **Market**: The region or market where the return occurred
* **Order ID**: The corresponding order ID from the Orders dataset

---

### 3. **People Dataset**

The **People** dataset provides information about employees and their regions. It links employee performance to regional sales performance and is useful for evaluating how different teams contribute to the overall business success.

**Key Columns**:

* **Person**: Name of the employee
* **Region**: Region in which the employee operates

---

## Dashboard Visualizations & Key Insights

### 1. **Sales Overview**

**Objective**: To give an overall snapshot of total sales and profitability across different categories and regions.

**Visuals**: <img width="558" height="82" alt="image" src="https://github.com/user-attachments/assets/4c868b17-716e-494e-8867-ef8ea9e8f134" />


* **Total Sales and Profit Trends**: Line graphs to track sales and profits over time.
* **Sales by Region and Category**: Bar charts showing performance across different regions and product categories.

### 2. **Return Rate Analysis**

**Objective**: To analyze return rates by product category, segment, and region to identify products or markets with higher return rates.

**Visuals**: <img width="610" height="428" alt="image" src="https://github.com/user-attachments/assets/d984d8b1-d16f-4390-a3d2-25987af38d2c" />


* **Return Rate by Product Category**: Bar chart comparing return rates for different categories.
* **Return Analysis by Region**: Pie or bar chart visualizing return rates by geographical market.

### 3. **Profitability by Product Category**

**Objective**: To identify the most profitable product categories, enabling better focus on high-performing products.

**Visuals**: <img width="567" height="387" alt="image" src="https://github.com/user-attachments/assets/868c0b36-18b7-4e03-b471-dc7d2bc0371b" />


* **Profit by Category**: Bar chart showing the total profit for each category.
* **Top Performing Categories**: Highlight the top 5 most profitable categories.

### 4. **Top/Bottom 5 Subcategories**

**Objective**: To identify the best and worst performing subcategories based on sales and profitability.

* **Top 5 Subcategories by Sales**: Bar chart showcasing the top 5 subcategories based on total sales.
**Visuals**: <img width="614" height="434" alt="image" src="https://github.com/user-attachments/assets/81cab740-2711-4ed9-87dd-e2de11f2205e" />

* **Bottom 5 Subcategories by Profitability**: Visualizing the least profitable subcategories to focus on operational improvements.
**Visuals**: <img width="614" height="434" alt="image" src="https://github.com/user-attachments/assets/03386beb-0e25-4c46-ac16-5c305bfe595d" />


### 5. **Sales and Profit Analysis (Problem Statement 2)**

**Objective**: To analyze how sales and profit align across different product categories, customer segments, and markets.

**Visuals**: <img width="610" height="428" alt="image" src="https://github.com/user-attachments/assets/258d82b3-06eb-4b3b-848a-90cac461c6e9" />


* **Sales vs Profit**: Scatter plot or line chart to compare sales and profit for each product category, segment, and market.

### 6. **Sales Performance by Country**

**Objective**: To evaluate sales performance on a global scale, comparing different countries' contributions to the business.

**Visuals**: <img width="721" height="433" alt="image" src="https://github.com/user-attachments/assets/a10d0fd7-0f05-4c6b-99ff-b681be38d31d" />


* **Sales by Country**: Bar chart displaying total sales by country.
* **Country-Wise KPI Overview**: A summary table or visualization highlighting key KPIs like sales, profit, and quantity sold by country.

### 7. **Yearly Sales Trends (Problem Statement 8)**

**Objective**: To evaluate year-on-year sales growth and performance, providing insights into annual trends.

**Visuals**: <img width="560" height="123" alt="image" src="https://github.com/user-attachments/assets/ce833206-1afe-44b6-baea-dcefee1af247" />


* **Year-on-Year Sales Comparison**: Line graph comparing sales performance over different years.

---

## Dynamic Features

### Dynamic Filters

The dashboard allows dynamic filtering of data based on time periods, customer segments, regions, and product categories, providing a flexible and interactive experience for users.

### KPI Summary Table

A dedicated section presents the **Key Performance Indicators (KPIs)** like total sales, total profit, quantity sold, and return rates. This summary serves as a quick reference to monitor overall business health.

---

## Further Enhancements & Next Steps

### Additional Features to Implement:

* **Top and Bottom Customers**: Create a detailed customer segmentation analysis to identify the highest and lowest spending customers.
* **Regional Performance**: Further break down sales by regional personnel performance, to understand the direct impact of each employee or team on sales.

### Recommendations for Future Extensions:

* **Product Return Analysis**: Extend return analysis by integrating reasons for returns to better understand product performance and customer satisfaction.
* **Employee Performance Analytics**: Create employee performance metrics that directly link to regional sales results, allowing better evaluation of individual contributions.

---

## Conclusion

The **Retail Performance Dashboard** offers an interactive and comprehensive view of retail performance across multiple dimensions. By leveraging the **Orders**, **Returns**, and **People** datasets, the dashboard helps in making data-driven decisions, improving sales strategies, reducing return rates, and enhancing operational efficiency.

---


