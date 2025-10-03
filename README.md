# 🛍️ Marketing Campaign Effectiveness (MCE) Analysis  

## 📌 Project Overview  
This project analyzes customer data from a retail marketing campaign to uncover insights into customer demographics, purchase behavior, and campaign performance.  
The goal is to **segment customers**, evaluate their purchasing patterns, and provide **business recommendations** for improving marketing strategies.

---

## 📂 Dataset  
- **Source:** Marketing Campaign dataset (`marketing_campaignc.csv`)  
- **Rows:** 2,240 customers  
- **Columns:** 29 features covering demographics, spending behavior, and campaign response  

### Key Features
- **Demographics**: `birth_year`, `education`, `marital_status`, `income`, `family composition`  
- **Purchase Behavior**: Spending on wine, fruits, meat, fish, sweets, and gold products  
- **Campaign Engagement**: Number of web, catalog, store purchases, and campaign responses  
- **Recency**: Days since last purchase  

---

## 🔑 Workflow  

1. **Data Understanding & Cleaning**  
   - Renamed columns for readability  
   - Handled missing values  
   - Converted dates and created customer tenure features  

2. **Feature Engineering**  
   - Derived `age`, `family_size`, `has_kids`  
   - Calculated total spending (`mnt_total`)  
   - Built recency & engagement metrics  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of age, income, and spending  
   - Correlation between income and product spending  
   - Analysis of campaign acceptance rates  

4. **Segmentation & Insights**  
   - Identified high-value customers (wine & gold buyers)  
   - Found differences in spending patterns across family composition  
   - Clustered customers based on purchase behavior  

---

## 📊 Key Insights  

- **Wine** is the top-selling product category  
- **High-income, no-kid households** spend the most on luxury items (wine & gold)  
- **Families with children** are more price-sensitive and respond better to discounts  
- **Campaign acceptance** is low (<15%), highlighting the need for **personalized marketing**  

---

## 🚀 Business Recommendations  

1. **Personalized Marketing**  
   - Target high-income, no-kid households with premium offers  
   - Families with children → bundle essentials (meat, fish, fruits)  

2. **Campaign Optimization**  
   - Reduce generic campaigns → focus on segmentation  
   - Loyalty rewards for repeat buyers  

3. **Cross-Selling**  
   - Pair wine with sweets/gold for luxury bundles  

---

## 🛠️ Tech Stack  

- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook** for analysis & visualization  
- **Scikit-learn** for clustering & segmentation  

---
