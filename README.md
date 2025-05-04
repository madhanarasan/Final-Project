##1.🏡 Airbnb Dynamic Pricing Recommendation Engine
A data-driven project to recommend optimal Airbnb listing prices based on location, seasonality, and listing quality. Built using Python, Tableau, and Excel.

**📌 Objective**
To analyze historical Airbnb data and suggest dynamic pricing strategies to hosts, helping maximize occupancy and revenue. Pricing recommendations are based on factors such as city, property type, review scores, and seasonal trends.

**🛠️ Tools & Technologies**
Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

Tableau (for interactive dashboard)

Excel (initial exploration & sanity checks)

**📊 Key Features**
Analyze average pricing by city, property type, and review score

Build a regression model to predict optimal pricing

Develop a dynamic pricing engine script

**Create an interactive Tableau dashboard with:**


Filters for city, property type, season

A price suggestion slider for listings
**📈 Model Summary**
A linear regression model was trained using key features such as:

Location (City, Neighborhood)

Property Type

Number of Reviews

Review Score

Season (month/quarter)

**Model performance metrics and tuning details can be found in the notebook:** airbnb.ipynb
**📑 Final Deliverables**
✅ Python script: pricing_engine.py

✅ Tableau dashboard: airbnb_dashboard.twbx

✅ Final report: Airbnb Dynamic Pricing Recommendation Report.pdf 



# 2 .🛒 E-commerce Return Rate Reduction Analysis

## 📋 Project Overview
This project analyzes e-commerce product returns to identify patterns and predict future returns.  
The goal is to help reduce return rates by understanding high-risk products, suppliers, and customer behavior.

Tools used:
- Python (Logistic Regression Model)
- Power BI (Interactive Dashboard with Drill-through)
- SQL (optional for deeper querying)
- Dataset: Synthetic e-commerce returns data

---

## 📁 Project Structure
```
ecommerce-return-rate-analysis/
│
├── return_risk_prediction.py        # Python code for data cleaning, modeling, and prediction
├── ecommerce_returns_synthetic_data.csv   # Raw dataset
├── high_risk_products.csv           # Exported high-risk products with return probabilities
├── ecommerce return risk analysis.pbix                   # Power BI dashboard file
├── README.md                         # Project documentation (this file)
```

---

## 📊 Dashboard Features
- **Return Rate % by Product Category, Geography, and Marketing Channel**
- **Drill-through filters** to deep dive into Product Details
- **High Risk Product List** showing products with a higher likelihood of return
- **Interactive Slicers**: Product Category, Payment Method, User Location, Gender

---

## 🔍 Python Code Highlights
- Data Cleaning and Feature Encoding
- Logistic Regression Model for Return Prediction
- Probabilistic Scoring of Orders
- Exporting high-risk products to CSV for analysis

Main Python libraries used:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---



## 📈 Business Insights
- Categories with high return rates identified for improvement.
- Return probability scoring enables better quality control and targeted promotions.
- Geographical trends highlight where return policies may need adjustments.

---

## ✍️ Author
**P.MADHANARASAN**
- Connect with me on [LinkedIn](https://linkedin.com/in/madhanarasanp3) (optional)

---
