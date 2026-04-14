# 🛍️ Customer Shopping Behavior Analysis



## 📌 1. Project Overview

This project focuses on analyzing customer shopping behavior to uncover meaningful insights that can drive business decisions. The dataset was cleaned, transformed, and analyzed using a complete data pipeline—from raw data processing to interactive dashboard creation.

The goal is to understand customer purchasing patterns, product performance, and revenue trends, and present them visually through an intuitive dashboard.



## 🛠️ 2. Tools and Technologies

* 🐍 **Python (Jupyter Notebook)** – Data cleaning and preprocessing
* 📊 **Pandas** – Handling missing values, transformations, and feature engineering
* 🗄️ **MySQL** – Data storage and advanced querying
* 📈 **Power BI** – Dashboard creation and data visualization


## 🔄 3. Project Steps

### 📥 Data Collection

* Imported raw CSV dataset into Jupyter Notebook

### 🧹 Data Cleaning & Preprocessing

* Handled missing values
* Standardized column formats
* Removed duplicates
* Created new derived columns (e.g., age groups, frequency mapping)

### 🗃️ Data Storage

* Exported cleaned dataset into MySQL database

### 🔍 Data Analysis (SQL)

Performed business-focused analysis such as:

* Revenue by gender
* Top-rated products
* Subscription vs non-subscription behavior
* Customer segmentation (New, Returning, Loyal)
* Product performance within categories
* Revenue contribution by age groups

### 📊 Dashboard Development

* Built an interactive Power BI dashboard
* Added filters for Gender, Category, Payment Type, Season
* Created KPIs like Revenue, Average Order Value, Satisfaction Score



## 📁 4. Project Structure

```
📦 Customer-Shopping-Behavior-Analysis
│
├── 📄 shopping_dataset.csv              # Raw dataset
├── 📓 customer_analysis.ipynb           # Data cleaning (Pandas)
├── 🗄️ customer_analysis.sql             # SQL queries & analysis
├── 📊 dashboard.pbix                   # Power BI dashboard file
├── 🖼️ dashboard.png                    # Dashboard preview
└── 📄 README.md                        # Project documentation
```



## 📊 5. Results & Insights

✨ **Key Findings:**

* 💰 **Total Revenue:** $233K generated across all customers
* 🛒 **Top Category:** Clothing contributes the highest revenue
* ⭐ **Best Rated Products:** Gloves, Sandals, and Boots lead in customer satisfaction
* 🔁 **Subscription Impact:** Subscribed customers show higher engagement and consistent purchases
* 👥 **Customer Segmentation:** Majority fall under returning customers
* 🌍 **Geographic Insight:** Certain states contribute significantly higher revenue
* 📦 **Purchase Frequency:** Monthly and quarterly buyers dominate

📌 These insights help businesses:

* Improve targeted marketing
* Optimize inventory
* Enhance customer retention strategies



## 🚀 6. Future Enhancements

* 🤖 Add **predictive analytics** (customer churn, sales forecasting)
* 📉 Implement **time-series analysis** for seasonal trends
* 🌐 Deploy dashboard to **Power BI Service** for live access
* 🧠 Integrate **machine learning models** for customer segmentation
* 📊 Add more advanced KPIs (LTV, CAC, retention rate)



## 📜 7. License

This project is licensed under the **MIT License** – feel free to use and modify for your own projects.



## 🙌 8. Acknowledgements

* 📚 Open-source datasets for providing realistic data
* 🐍 Python & Pandas community for data handling support
* 🗄️ MySQL for efficient querying
* 📊 Power BI for powerful visualization capabilities



💡 *If you like this project, feel free to ⭐ the repository and share your feedback!*
