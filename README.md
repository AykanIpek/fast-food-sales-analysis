# Fast-Food Sales Analysis

Author: **AykanIpek**  
Repository: **fast-food-sales-analysis**  

---

## 📌 Project Overview
This project focuses on analyzing sales data from a fast-food restaurant chain using **Python**, **SQLite**, and various **data visualization tools**.  
It demonstrates the complete data science workflow: from ingestion and cleaning to feature engineering, exploratory data analysis (EDA), and preliminary modeling.

---

## ⚙️ Workflow

### 1. Data Ingestion & Storage
- Multiple CSV datasets are imported into **SQLite** tables.  
- Structured tables include:
  - Menu details  
  - Store information  
  - Sales transactions  
  - Item-level sales  

### 2. Data Cleaning & Integration
- SQL joins used to merge datasets on keys.  
- Missing values and inconsistent data types checked.  
- Additional computed columns added for richer insights.  

### 3. Feature Engineering
- Dates converted into `datetime` objects.  
- Extracted features: **day, month, numeric date values**.  
- Aggregated daily revenues at:
  - Per-store level  
  - Overall chain level  

### 4. Exploratory Data Analysis (EDA)
- **Time series plots** → daily revenue trends by store and state.  
- **Distribution plots & countplots** → transaction frequencies and revenue spread.  
- **Pie charts** → store contributions to overall revenue.  
- **Bar plots** → top-selling menu items.  
- **Correlation heatmaps** → relationships between numerical features.  

### 5. Modeling (Initial Setup)
- Prepared dataset for predictive modeling.  
- Tested initial models:
  - **Linear Regression**  
  - **Random Forest Regressor**  

---

## 📊 Visualization Tools
- **Matplotlib** & **Seaborn** → static plots.  
- **Plotly Express** → interactive visualizations.  

---

## 🚀 Key Insights
- Revenue patterns vary significantly across stores and states.  
- Certain menu items consistently dominate sales.  
- Aggregated daily sales reveal seasonal/temporal demand trends.  

---

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy, Scikit-learn)  
- **Database:** SQLite  
- **Visualization:** Matplotlib, Seaborn, Plotly Express  

---

## 📂 Repository Structure
```
fast-food-sales-analysis/
│── data/                 # Raw CSV datasets
│── notebooks/            # Jupyter notebooks with analysis
│── scripts/              # Python scripts for ETL & modeling
│── results/              # Plots and outputs
│── README.md             # Project documentation
```

---

## ✅ Conclusion
This project showcases how **data ingestion, cleaning, feature engineering, visualization, and modeling** can be applied to a real-world retail dataset.  
The insights provide valuable guidance for understanding **revenue drivers** and **top-performing products** in a fast-food chain.

---
