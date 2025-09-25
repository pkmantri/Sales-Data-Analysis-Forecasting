# 📊 Sales Data Analysis & Forecasting

## 📌 Project Overview
This project focuses on **analyzing sales data** to uncover key business insights such as top-performing products, regional performance, seasonal sales trends, and forecasting.  
It simulates the type of business analytics projects often handled by IT consulting companies like **Cognizant, Accenture, and Deloitte**.  

The goal is to demonstrate **data analysis, SQL querying, and visualization skills** using Python.

---

## 🛠️ Tech Stack
- **Programming Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib  
- **Database/Queries:** SQL (SQLite / MySQL)  
- **Tools:** Jupyter Notebook / VS Code  

---

## 🔑 Features
✔️ Data cleaning & preprocessing (handling missing values, formatting dates)  
✔️ **Top-performing products** analysis  
✔️ **Regional sales comparison** (North, South, East, West)  
✔️ **Monthly/seasonal sales trends** visualization  
✔️ SQL queries for top products & regional insights  
✔️ **Simple forecasting** using moving averages  

---

## 📂 Project Structure
```
├── sales_data.csv              # Sample dataset
├── sales_analysis.ipynb        # Main analysis notebook
├── requirements.txt            # Dependencies
├── README.md                   # Project documentation
```

---

## 📊 Sample Analysis

### 1. Top Products by Revenue
```sql
SELECT Product, SUM(Sales) AS Total_Revenue
FROM sales
GROUP BY Product
ORDER BY Total_Revenue DESC
LIMIT 5;
```

### 2. Monthly Sales Trend (Python + Pandas)
```python
monthly_sales = df.groupby("Month")["Sales"].sum()
monthly_sales.plot(kind="line", marker="o", title="Monthly Sales Trend")
```

📈 *Insight:* Peak sales were observed during festive months, showing strong seasonality.  

---

## 📈 Forecasting
- Used a **3-month moving average** to forecast future sales.  
- Identified upward/downward trends in product demand.  
- Highlighted **limitations** (not suitable for sudden spikes, seasonal promotions).  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sales-data-analysis.git
   cd sales-data-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook sales_analysis.ipynb
   ```

---

## 📌 Key Learnings
- Hands-on practice with **Python (Pandas, NumPy, Matplotlib)**.  
- Used **SQL for business-style queries**.  
- Extracted **business insights** from raw data.  
- Created visualizations to support **decision-making**.  
- Built a basic **forecasting model** to predict sales trends.  


---
👨‍💻 Developed by **Pankaj kumar Mantri** | 📧 your.email@pkmantriwrk06@gmail.com
