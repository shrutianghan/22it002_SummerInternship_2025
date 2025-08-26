# 🛒 Sales Analysis  

## 📌 Project Overview  
This project performs an **in-depth analysis of e-commerce sales data** using Python.  
The dataset contains two files:  

1. **Orders.csv** → Customer order details (Order ID, Order Date, Customer, State, Payment Mode, etc.)  
2. **Details.csv** → Transaction-level details (Order ID, Product, Category, Sub-category, Amount, Quantity, Profit, etc.)  

The project includes:  
- 📊 **Exploratory Data Analysis (EDA)**  
- 📈 **Sales & Profit Trends**  
- 📍 **Geographical and Customer Insights**  
- 🎯 **Key Performance Indicators (KPIs)**  
- 📝 **Business Insights & Conclusion**  

---

## 🗂️ Project Structure  

```
Ecommerce-Sales-Analysis/
│
├── Orders.csv               # Orders dataset
├── Details.csv              # Details dataset
├── Ecommerce_Sales_Analysis.ipynb  # Main Colab Notebook
├── README.md                # Project Documentation
└── requirements.txt         # Required Python packages
```

---

## ⚙️ Installation & Setup  

1. Open the notebook in **Google Colab** (recommended).  
2. Upload both datasets (`Orders.csv` and `Details.csv`).  
3. Run all cells in order.  

**Dependencies** (already available in Colab):  
```bash
pandas
numpy
matplotlib
seaborn
```

---

## 🔎 Exploratory Data Analysis (EDA)  

The EDA section covers:  
- **Data Overview** → shape, columns, missing values, duplicates.  
- **Descriptive Statistics** → mean, median, quartiles, distributions.  
- **Univariate Analysis** → frequency of categories, histograms, boxplots.  
- **Bivariate Analysis** → correlation heatmap, scatterplots, barplots.  
- **Time Series Analysis** → monthly & weekly sales trends.  
- **Geographical Insights** → top states and cities by revenue.  
- **Customer Insights** → top customers, repeat orders.  

---

## 📊 KPI Dashboard  

The following KPIs are calculated:  
- Total Sales  
- Total Profit  
- Number of Orders  
- Unique Customers  
- Average Order Value (AOV)  
- Profit Margin (%)  

---

## 📝 Insights  

- Sales show **seasonal and monthly variations**.  
- **Furniture & Technology** categories generate the highest sales.  
- A small number of **states and cities dominate revenue**.  
- Certain **sub-categories are highly profitable**, while others drive volume.  
- **Top customers** contribute significantly to sales.  
- Payment mode preferences differ across customers.  

---

## ✅ Conclusion  

This project demonstrates how to perform **end-to-end sales analysis** using Python and visualize results in a clear way.  
It can be extended further by:  
- Predictive modeling (forecasting sales).  
- Customer segmentation.  
- Profit optimization strategies.  

---

## 👨‍💻 Author  
*Shruti Anghan*   
