# 🛒 Retail Orders Analysis Project

=====================================

This project focuses on analyzing a retail order dataset using Python (Pandas), SQL, and SQLite. The analysis uncovers patterns and insights from customer orders including shipping trends, customer segments, and order volumes. This project showcases skills in data cleaning, EDA (Exploratory Data Analysis), SQL querying, and data visualization.
This project is a complete **retail sales data analysis pipeline** using **Python, SQL, Pandas, and Matplotlib/Seaborn**. It covers everything from raw data cleaning to generating insights and visualizations, aimed at understanding key aspects of customer behavior, order patterns, and shipping modes.

---

## 📁 Project Structure

PROJECT_04_RETAIL_ORDERS/
│
├── orders.csv # Original raw dataset
├── cleaned_orders.csv # Cleaned version of the dataset
├── orders.db # SQLite database created from the dataset
├── SQL_queries.txt # Collection of SQL queries used in analysis
├── Retail_Orders.ipynb # Jupyter notebook with code & visualizations
├── README.md # Project summary (this file)
└── Visualizations/ # (Optional) Folder containing saved plots

---

---

## 🧠 Objective

To perform detailed analysis on retail order data and extract meaningful insights regarding:

- Sales performance
- Customer segments
- Shipping methods
- City-wise distribution
- Trends over time

- Clean and explore the raw dataset
- Perform SQL-based querying for deeper insights
- Analyze customer segments, shipping trends, and geography
- Visualize key trends using Python libraries

---

## 🛠️ Tools and Technologies

- **Python 3.12+**
- **Jupyter Notebook (VS Code)**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **SQLite** for SQL database operations
- **SQL** for querying structured data

---

## 🔍 Step-by-Step Workflow

### 1. **Loading the Dataset**

- Imported the dataset (`orders.csv`) using `pandas.read_csv()`
- Displayed top 10 rows using `.head(10)`

### 2. **Data Cleaning**

- Checked for missing values and duplicates
- Handled missing values
- Renamed columns for consistency
- Ensured correct data types (e.g., `datetime`)
- Exported the cleaned version as `cleaned_orders.csv`

### 3. **Exploratory Data Analysis (EDA)**

- Analyzed customer **segments**
- Identified popular **shipping modes**
- Examined **order distribution** across cities and dates
- Created visualizations for insights:
  - Bar plots for shipment mode counts
  - Pie charts for segment distribution
  - Line graphs for order trends over time

### 4. **SQL Queries**

- Created `orders.db` using SQLite
- Imported cleaned CSV into a table
- Wrote various SQL queries to:
  - Count total orders
  - Get top cities by order volume
  - Segment-wise order distribution
  - Orders grouped by shipping mode

### 5. **Final Deliverables**

- `Retail_Orders.ipynb`: Notebook with all steps
- `SQL_queries.txt`: All queries saved in a separate file
- `orders.db`: Ready-to-use database
- `cleaned_orders.csv`: Cleaned dataset for reuse

---

## 📈 Key Insights

- **Standard Class** is the most used shipping method.
- **Consumer segment** accounts for the highest number of orders.
- Cities like **Los Angeles** and **Henderson** show high order volumes.
- There are missing/invalid shipping methods (e.g., "Not Available"), which may indicate data quality issues.

---

## 📦 How to Use

1. Clone or download this repository.
2. Open the Jupyter Notebook (`Retail_Orders.ipynb`) in VS Code or Jupyter Lab.
3. Install dependencies:  

   ```bash

   pip install pandas matplotlib seaborn sqlite3

---

   Run the notebook step by step.

   Explore the database using the built-in SQLite extension (VS Code) or DB Browser for SQLite.

📚 Learning Outcomes
Practiced end-to-end data analysis.

Learned how to combine Pandas with SQL queries.

Structured and documented a complete mini-project.

Prepared for sharing on GitHub & Kaggle portfolios.

Next Steps:
 Final review and validation

 Upload to GitHub with proper commits

 Share on Kaggle as a public dataset + notebook

📬 Contact:
If you have any suggestions or questions, feel free to connect with me:

GitHub: Qazi-Hassan

Kaggle: your-kaggle

Email: [a927hassan@gmail.com](mailto:a927hassan@gmail.com)
