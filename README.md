# 📊 Retail Sales & Profit Analysis  

## 📌 Overview  
This project analyzes retail sales data to uncover insights into **profitability, discount effectiveness, customer segments, regional performance, and shipping trends**.  
Additionally, the project implements **K-Means clustering** for product segmentation and an **ARIMA time-series forecasting model** to predict future monthly sales.  

The goal is to provide data-driven **recommendations to improve profitability** and guide future business decisions.  

---

## 🛠️ Tech Stack  

- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – K-Means clustering  
- **pmdarima / statsmodels** – ARIMA forecasting  
- **Jupyter Notebook** – Interactive analysis  

---

## 🗂️ Project Structure  

- **Data Preprocessing & Cleaning**  
  - Handling missing values  
  - Aggregating sales by time and category  
  - Feature engineering for discounts, profit margins, and delivery times  

- **Exploratory Data Analysis**  
  - Monthly sales & profit trends  
  - Discounts vs. sales/profit correlations  
  - Category, segment, and regional performance breakdowns  
  - Shipping mode and delivery time distribution  

- **Clustering (K-Means)**  
  - Product segmentation based on **sales, profit, and discount rates**  
  - Identification of high-performing vs. underperforming product groups  

- **Time-Series Forecasting (ARIMA)**  
  - Forecasting **future monthly sales trends**  
  - Model selection with `pmdarima` auto-ARIMA  
  - Visualization of projected performance  

- **Conclusion & Recommendations**  
  - Summary of findings across sales, categories, customers, and regions  
  - Strategic recommendations to reduce discount losses and improve margins  

---

## 📊 Key Insights  

- **Discounts are largely ineffective**, often leading to lower profit margins without increasing sales.  
- **Copiers** are top performers with strong profitability, while categories like **Binders, Machines, and Tables** underperform due to excessive discounts.  
- **Furniture as a category is less profitable** compared to Technology and Office Supplies.  
- **Vermont** excels with zero discounts and high profit margins, while **Wyoming and Texas** underperform due to heavy discounting.  
- **Customer segments show similar profit margins**, suggesting that segment-specific pricing strategies may not be impactful.  
- **Shipping modes** behave as expected, but **same-day shipping shows some failures**.  
- **ARIMA forecasts** predict a promising and more stable upward trend in sales for the coming year.  

---

## 🚀 Recommendations  

1. **Reduce unnecessary discounting**, especially in underperforming categories.  
2. **Expand profitable product lines** such as Copiers.  
3. **Reevaluate Furniture category** for long-term strategy.  
4. **Target improvements in underperforming regions** (e.g., Texas, Wyoming) by reducing discounts and improving margin strategies.  
5. **Ensure same-day shipping reliability** to maintain customer trust.  
6. **Leverage upcoming sales growth** (as forecasted) by focusing on profit margin improvements instead of relying on raw sales volume.  

---


## 📈 Example Visualizations  

- Monthly sales and profit trends  
- Discounts vs. profit correlation heatmap  
- K-Means cluster segmentation of products  
- ARIMA forecast of future sales  

---

## 📌 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/KyleNicholls19/StoreDataAnalysis.git
   cd StoreDataAnalysis
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
4. Open and Run `StoreDataAnalysis.ipynb`
