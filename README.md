# 🛍 Ecommerce Customer Spending Analysis

This project analyzes customer behavior data to determine whether an eCommerce company should focus on improving its **mobile app** or **website** experience. The goal is to predict yearly customer spending using various engagement metrics.

---

## 📊 Project Overview
The dataset contains customer details such as:
- **Avg. Session Length** — Average time spent in in-store sessions  
- **Time on App** — Average time spent on the mobile app  
- **Time on Website** — Average time spent on the website  
- **Length of Membership** — Duration of customer membership  
- **Yearly Amount Spent** — Annual customer spending (Target Variable)

---

## 🎯 Business Objective
To interpret which variables contribute most to yearly income prediction and to build a machine learning model that helps the company decide its focus area (App vs Website).

---

## 🧪 Methodology
1. **Data Cleaning & EDA**
   - Removed unwanted features (`Email`, `Address`, `Avatar`)
   - Checked for missing values and outliers
   - Visualized correlations between variables

2. **Modeling**
   - Compared multiple regression models: Linear, Ridge, and Lasso
   - Selected **Linear Regression** as the final model (best R² and RMSE balance)

3. **Deployment**
   - Model prepared for deployment using Streamlit.

---

## 🧰 Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- PowerPoint for Presentation
- Streamlit (for deployment)

---

## 📁 Repository Structure
