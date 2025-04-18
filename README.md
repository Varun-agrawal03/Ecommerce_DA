
# E-commerce Data Analysis with Python & MySQL

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)](https://www.mysql.com/)  

A data analytics project that loads e-commerce CSV data into MySQL using Python, then performs powerful SQL and Python-based analysis to extract business insights.

---

##  Dataset

The dataset is available on **Kaggle**:  
🔗 [Target E-commerce Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)

It includes:
- `customers.csv`
- `orders.csv`
- `sales.csv`
- `products.csv`
- `delivery.csv`
- `payments.csv`

---

##  Project Structure

```
├── csv_to_sql.py              # Script to convert CSV files to MySQL tables
├── ecommerce.ipynb            # Jupyter Notebook for analysis and visualization
├── dataset_link.txt           # Link to Kaggle dataset
├── Questions.txt              # List of analytical questions solved in notebook
├── requirements.txt           # Python dependencies
```

---

##  Setup Instructions

1. **Clone this repo** and download the dataset into the folder `SQL-Python-Ecommerce-Project-main`.

2. **Create a MySQL database**:
   ```sql
   CREATE DATABASE ecommerce;
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the data loader**:  
   Update credentials in `csv_to_sql.py` and run:
   ```bash
   python csv_to_sql.py
   ```

---

## 📊 Analysis Overview

Analysis is performed in the `ecommerce.ipynb` notebook using SQL queries and Python visualization libraries.

### 🔍 Key Business Questions Answered

(See `Questions.txt` for full list)

1. 🏙️ Unique cities where customers live  
2. 📦 Number of orders in 2017  
3. 💰 Total sales per category  
4. 💳 Installment payment analysis  
5. 🌎 Customers per state  
6. 📆 Monthly order trends  
7. 📈 Price vs purchase correlation  
8. 🧾 Revenue by seller  
9. 🔄 Customer retention rate  
10. 🥇 Top spenders each year  
... and more!

---

## 📚 Technologies Used

- **Python**: pandas, numpy  
- **MySQL**: Data storage and querying  
- **Jupyter Notebook**: EDA and exploration  
- **Matplotlib / Seaborn**: Visualization  

---

## 🚀 Future Improvements

- Dashboard (Streamlit/Dash)  
- ETL automation  
- PostgreSQL/SQLite support  
- Real-time querying via API  


---

> Built by **VARUN**
