# E-Commerce Sales Analysis

## 📌 Overview
This project analyzes e-commerce sales data to extract valuable business insights. Using **Power BI**, we examine **customer behavior, product performance, and sales trends** to help businesses optimize operations, inventory, and marketing strategies.

## 🔍 Problem Statement
E-commerce businesses need to understand customer behavior, product performance, and sales trends to optimize their operations. This project aims to analyze an E-Commerce sales data to gain insights into customer purchasing patterns, product popularity, geographic trends, sales strategies, inventory management, and customer satisfaction.

## 🎯 Objectives
- Perform **sales analysis** to determine revenue-generating products.
- Identify customer **shopping patterns** and segment users based on location.
- Provide **business recommendations** to improve profitability.

## 📊 Dataset Overview
The dataset was obtained from [FakeStore API](https://fakestoreapi.com) and consists of three key tables:

1. **Products Table**: Contains product details such as name, category, price, and rating.
2. **Carts Table**: Stores transaction details like purchase date, product quantity, and user ID.
3. **Users Table**: Holds customer information such as location, email, and demographics.

### 🔗 **Key Relationships**:
- `Carts.products.productId` ↔ `Products.Product_id`
- `Carts.userId` ↔ `Users.id`

## 🛠️ Methodology
1. **Data Collection**: Extracted API data from FakeStore.
2. **Data Cleaning & Processing**: Corrected data types, created key **DAX measures**, and normalized information.
3. **Data Modeling**: Established relationships between tables in Power BI.
4. **Data Analysis & Visualization**: Created reports and dashboards to extract insights.
5. **Interpretation & Recommendations**: Derived business insights and suggested optimization strategies.

## 📊 Key Insights & Business Recommendations

### 🔹 **Sales Performance & Revenue Trends**
- **Best-Selling Categories**: Men's Clothing and Jewelry generate the highest revenue.
- **Underperforming Categories**: Electronics and Women's Clothing have lower sales.
- **📌 Recommendation:** Offer targeted promotions and bundling for slow-moving products.

### 🔹 **Geographic Insights**
- **High concentrations of orders in Kilcoole and San Antonio**.
- **📌 Recommendation:** Focus marketing campaigns and inventory distribution in these areas.

### 🔹 **Pricing & Rating Impact**
- Products with **higher ratings sell more**, showing customer trust in quality.
- **📌 Recommendation:** Encourage customer reviews and improve product quality.

## 📊 Power BI Dashboard Highlights
- **Sales Overview**: Total revenue, top products, and category-wise sales.
- **Customer Insights**: Purchase frequency, average order value, and segmentation.
- **Geographical Analysis**: Doughnut chart of customer locations and regional sales trends.
- **Time-Based Trends**: Monthly and daily sales performance.

  ![Screenshot 2025-03-15 232106](https://github.com/user-attachments/assets/fbb58462-6927-43ce-9e01-9eadd7933f24)


## 🚀 Future Work
- **Predictive modeling**: Use Machine Learning to forecast future sales trends.
- **Customer churn analysis**: Identify customers at risk of leaving.
- **Competitor Benchmarking**: Compare performance against similar e-commerce businesses.


## 📌 How to Use
1. Open **Power BI Desktop**.
2. Load the `.pbix` file.
3. Explore **interactive dashboards and insights**.

---
🔗 Check out the full project report: [https://github.com/Samuel-adeboje/E-Commerce-Sales-Analysis/blob/main/E-Commerce%20Sales%20Analysis%20Report.pdf]

🔗 Connect with me on LinkedIn: [www.linkedin.com/in/samuel-adeboje-368320330]
