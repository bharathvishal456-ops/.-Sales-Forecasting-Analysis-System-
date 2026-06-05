# **Sales Forecasting Analysis System**  
*Exploratory Data Analysis (EDA) for Business Decision Support using Kaggle Sales Dataset*

---

## **Overview**

Manual analysis of business sales data is time-consuming and often leads to inaccurate forecasting decisions. Organizations generate large volumes of historical sales data across stores, products, and dates, making it difficult to extract meaningful insights without automated analytics.

This project focuses on building a **Sales Forecasting Analysis System** that performs **Exploratory Data Analysis (EDA)** on a real-world Kaggle dataset to understand sales trends, identify high-performing products and stores, and support future forecasting decisions.

By analyzing historical sales data, the system detects seasonal patterns, peak sales periods, and relationships between stores, products, and time, helping businesses make data-driven decisions and improve inventory and marketing strategies.

The workflow includes:

- Data Collection: Loading Kaggle sales dataset
- Data Cleaning: Handling missing values and inconsistencies
- Statistical Analysis: Understanding sales distribution
- Trend Analysis: Identifying seasonal and time-based patterns
- Store/Product Comparison: Evaluating performance
- Visualization: Charts, heatmaps, and trend graphs
- Business Insights: Supporting forecasting decisions

---

## **Dataset**

**Source:** Kaggle  
**Dataset Link:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting  
**Dataset Name:** Sales Forecasting Dataset  

**Description:**  
The dataset contains historical sales records including transaction dates, store IDs, product IDs, and number of items sold.

### **Selected Columns**

- Date  
- Store  
- Item  
- Sales  
- Region (if available)

### **Removed Columns**

- Unnecessary IDs  
- Metadata columns  
- Extra unused attributes  

The selected columns simplify the dataset and improve analysis clarity.

---

## **Objectives**

1. **Data Collection**
   - Load sales dataset from Kaggle
   - Understand structure and features

2. **Data Cleaning & Preprocessing**
   - Check missing values
   - Convert Date to datetime format
   - Remove duplicates
   - Handle inconsistencies

3. **Descriptive Statistics**
   - Total sales
   - Average sales
   - Maximum and minimum sales
   - Sales distribution

4. **Sales Trend Analysis**
   - Analyze sales over time
   - Identify seasonal patterns
   - Detect peak sales periods

5. **Store/Product Analysis**
   - Compare store performance
   - Identify best-selling products
   - Detect low-performing products

6. **Time-Based Analysis**
   - Daily trends
   - Monthly trends
   - Yearly growth

7. **Relationship Analysis**
   - Date vs Sales
   - Store vs Sales
   - Product vs Sales
   - Pattern identification

8. **Data Visualization**
   - Line charts
   - Bar charts
   - Histograms
   - Box plots
   - Heatmaps

9. **Business Insights**
   - Peak sales seasons
   - High-performing stores/products
   - Sales fluctuations

10. **Insights & Conclusion**
   - Overall sales behavior
   - Forecasting support
   - Business strategy improvement

---

## **Project Highlights**

### **1. Data Collection & Cleaning**

- Dataset loaded from Kaggle
- Date column converted into datetime format
- Missing values checked and handled
- Duplicate records removed
- Clean dataset prepared for analysis

This step ensures data reliability and accuracy.

---

### **2. Exploratory Data Analysis (EDA)**

- Total and average sales calculated
- Store-wise and product-wise performance analyzed
- Monthly and yearly sales trends examined
- Seasonal sales patterns identified
- Relationship between date and sales explored

EDA helps understand business performance and market demand patterns.

---

### **3. Visualization**

The project includes:

- **Line Charts** – Sales trend over time
<img width="1700" height="590" alt="image" src="https://github.com/user-attachments/assets/cb352d8a-6d8a-439f-998d-1327bb2255d1" />

- **Bar Charts** – Store and product comparison
<img width="1700" height="591" alt="image" src="https://github.com/user-attachments/assets/bb28f890-d322-4610-a21c-2ac004abcaab" />

- **Histograms** – Sales distribution
<img width="1693" height="585" alt="image" src="https://github.com/user-attachments/assets/71f4455e-af4a-46f6-b586-315e565e5327" />

- **Box Plots** – Outlier detection
<img width="1694" height="587" alt="image" src="https://github.com/user-attachments/assets/3196dba8-ba3b-4763-8819-24184a437938" />

- **Heatmaps** – Correlation between features
<img width="1699" height="586" alt="image" src="https://github.com/user-attachments/assets/45b58df2-4d25-48b0-87d7-b9ef0af6128d" />

Visualizations make complex sales data easy to interpret and understand.

---

## **Tools and Technologies**

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Jupyter Notebook  
- Google Colab  
- Kaggle Dataset  
- CSV File Storage

---

## **Results**

### **Key Findings**

- Sales Trends: Sales show consistent seasonal patterns across months and years.  
- Peak Periods: Certain months and stores generate significantly higher sales.  
- Product Performance: A small group of products contributes to a large percentage of total revenue.  
- Store Comparison: Some stores consistently outperform others.  
- Outliers: Extreme sales spikes were detected during specific periods.  
- Correlation: Time-based factors strongly influence sales behavior.

---

### **Interpretation**

- Inventory Planning: Businesses can stock products based on seasonal demand.  
- Marketing Strategy: Promotions can be targeted during peak sales periods.  
- Store Optimization: Low-performing stores can be improved using data insights.  
- Forecasting Support: Historical patterns help predict future sales.  
- Decision Making: Automated EDA improves business planning and reduces risk.

The structured EDA approach enhances forecasting accuracy and business intelligence.

---

## **Conclusion**

The **Sales Forecasting Analysis System** successfully analyzes historical sales data and provides valuable insights for business decision-making.

Through structured **EDA and visualization**, the system identifies trends, seasonal patterns, and product performance, enabling companies to improve inventory management, marketing strategies, and forecasting accuracy.

This project demonstrates how **data analytics and visualization can transform raw sales data into actionable business intelligence**.

---

## **Author**

**Shree Pranava Ganesh**  
Student at Kamaraj College  
Thoothukudi, Tamil Nadu
