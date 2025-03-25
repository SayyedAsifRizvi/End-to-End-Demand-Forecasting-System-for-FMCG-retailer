# 📊 Demand Forecasting System for FMCG Retailer 🚀

![Demand Forecasting](https://img.shields.io/badge/Forecasting-ML-blue) ![Inventory Optimization](https://img.shields.io/badge/Inventory-Optimization-green) ![Python](https://img.shields.io/badge/Python-🐍-yellow)

## 📌 Overview
This project presents an **end-to-end demand forecasting solution** designed to optimize inventory management for a large **FMCG (Fast Moving Consumer Goods) retailer**. Using **machine learning (XGBoost, LSTM, ARIMA)** and **historical sales data**, this system accurately predicts future demand, ensuring **optimal inventory levels** and minimizing the risks of **overstocking and understocking**. 

## 🛒 Problem Statement
The retailer has been facing **significant losses** due to inefficient inventory management, leading to:
- 📦 **Overstocking**, increasing storage costs and wastage.
- 🏬 **Understocking**, resulting in lost sales and dissatisfied customers.

### 🎯 **Objective**
The goal is to develop a robust **demand forecasting system** that:
- Predicts **weekly demand** for different product categories.
- Helps optimize inventory levels.
- Reduces operational costs and maximizes profitability.

---

## 🔬 Project Methodology (CRISP-DM Approach)
This project follows the **CRISP-DM (Cross Industry Standard Process for Data Mining)** framework:

| Phase                | Description |
|----------------------|-------------|
| **📌 Business Understanding**  | Identified key inventory management pain points for a large FMCG retailer. |
| **📊 Data Understanding & Integration** | Used **BigQuery** as the primary data source, integrating it with **Google Colab** for SQL and Python-based data handling. |
| **🔍 Data Preparation** | Conducted **Exploratory Data Analysis (EDA)** and applied **time-series feature engineering** (lags, moving averages). |
| **📈 Modeling & Evaluation** | Built forecasting models using **XGBoost, LSTM, ARIMA**, evaluated with **RMSLE (Root Mean Squared Logarithmic Error)**. |
| **🚀 Deployment** | Developed a **Streamlit web app** hosted on **AWS** for real-time demand predictions. |

---

## 🗂️ **Data Sources**
This project uses three primary datasets:

| Dataset        | Description |
|---------------|-------------|
| **📦 Product Data** | Includes product ID, description, manufacturer, category, size, and pricing. |
| **📊 Sales Data** | Weekly sales at the store level, including promotions, discounts, and units sold. |
| **🏬 Store Data** | Store attributes like location, size, and market segmentation. |

👉 **Data integration was done using SQL in BigQuery**, enabling seamless data preprocessing.

---

## 🏗️ **Tech Stack & Tools**
### 🔢 **Data Handling & Processing**
- **Python** 🐍
- **SQL** (BigQuery)
- **Pandas**, **NumPy**

### 🏋️ **Machine Learning & Forecasting**
- **XGBoost**
- **LSTM (Deep Learning)**
- **ARIMA (Traditional Time-Series Model)**

### 🎛 **Optimization & Simulations**
- **Linear & Non-Linear Optimization**
- **Monte Carlo Simulations**
- **Route Optimization (Logistics)**

### 📊 **Visualization & Deployment**
- **Power BI** 📊 (Dashboards & Reports)
- **Streamlit** 🚀 (Web App)
- **AWS** ☁️ (Hosting & Scalability)

---

## 📌 **Key Features**
✅ **Accurate demand forecasting** using ML & time-series models.  
✅ **Optimized inventory management** with intelligent stocking strategies.  
✅ **Scalable ETL pipelines** for seamless data processing.  
✅ **Web-based dashboard** for real-time insights and decision-making.  

---

## 🎯 **How to Run the Project**
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/demand-forecasting-fmcg.git
cd demand-forecasting-fmcg
