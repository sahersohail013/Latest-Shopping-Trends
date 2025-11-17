# 🛍️ Customer Shopping Trends Analysis  
Exploratory Data Analysis (EDA) using **Python** and **Power BI**

This project analyzes the **Customer Shopping Latest Trends** dataset from Kaggle to uncover insights into purchasing behavior, customer demographics, spending patterns, and revenue drivers. Using Python for data exploration and Power BI for interactive dashboards, the project provides a complete end-to-end analytics workflow.

---

## 📂 Dataset  
**Source:** Kaggle  
🔗 https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset  

**Rows:** 3,900  
**Columns:** 19  
**Content Includes:**  
- Customer demographics (Age, Gender, Location)  
- Purchase details (Item, Category, Amount)  
- Preferences (Size, Color, Season, Payment Method)  
- Behavioral metrics (Previous Purchases, Review Rating)  
- Engagement metrics (Discounts, Subscription Status, Promo Codes)

No missing values.  
No duplicates.  
Clean dataset → ready for analysis.

---

## 🎯 Project Objectives  
- Understand customer behavior and shopping preferences  
- Analyze spending patterns across demographics, categories, and seasons  
- Identify top-selling items and categories  
- Explore the impact of discounts and shipping types  
- Build meaningful visualizations in Python  
- Create interactive dashboards using Power BI

---

## 🛠️ Tools & Technologies  
- **Python**: Pandas, Matplotlib, Seaborn  
- **Jupyter / Google Colab**  
- **Power BI** (for dashboard creation)  
- **Kaggle API** (for dataset download)

---

## 📊 Python Analysis Workflow

### ✔ 1. Importing & Loading Data
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv('/content/shopping_trends.csv')
