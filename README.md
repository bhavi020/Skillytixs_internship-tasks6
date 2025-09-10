# Sales Data Analysis with SQL in Python 📊

This project demonstrates the process of analyzing sales data using **SQL queries within Python** and visualizing the results.  
The dataset used (`sales_summary.csv`) contains product-wise sales details.

---

## 📂 Workflow of the Notebook

### 1. Task Definition
The main goal was to analyze the sales data and find:
- Total quantity sold per product
- Total revenue generated per product
- Visualize the revenue distribution with a bar chart

---

### 2. Data Loading
- The dataset was loaded from a CSV file into a **Pandas DataFrame**.  
- The first few records were displayed to understand the structure of the data.

---

### 3. Creating SQLite Database
- An **in-memory SQLite database** was created.  
- The DataFrame was stored as a SQL table named **`sales`** for running SQL queries directly.

---

### 4. Running SQL Queries
- A query was written to calculate:
  - **Total quantity sold** (sum of all quantities per product)  
  - **Total revenue** (sum of revenue per product)  
- The results were grouped by product and stored in a summary DataFrame.

---

### 5. Visualization
- The summarized results were visualized using a **bar chart**.  
- The chart displayed **revenue per product**, making it easier to compare product performance.

---

## 🔑 Key Learnings
- How to integrate **SQL with Python** using SQLite.  
- Using SQL queries to aggregate and analyze tabular data.  
- Converting query results back into a Pandas DataFrame for further analysis.  
- Visualizing data insights with **Matplotlib**.  

---

## 📊 Outcome
- A clear table showing **product-wise total quantity and revenue**.  
- A bar chart showing **revenue distribution across products**.  

---

## 🛠️ Requirements
- Python 3.x  
- Jupyter Notebook  
- Libraries: pandas, sqlite3, matplotlib  

---
