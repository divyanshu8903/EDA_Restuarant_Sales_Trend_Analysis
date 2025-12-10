# 🍽️ Restaurant Sales Analysis — EDA Project

This project performs **Exploratory Data Analysis (EDA)** on restaurant sales data to uncover insights related to customer behavior, revenue trends, and category performance.  
The analysis includes cleaning the dataset, handling missing values, visualizing sales patterns, and identifying key revenue contributors.

---

## 📊 Project Objectives

- Understand the structure of the dataset  
- Identify missing or duplicate values  
- Clean and preprocess the data  
- Perform univariate and multivariate analysis  
- Explore category-wise performance  
- Visualize insights to support decision-making  

---

## 🔍 Key Insights from the Analysis

- The dataset initially contained missing values, especially in the `transaction_type` column.
- No duplicate entries were detected.
- Fast food emerged as the **most purchased and highest revenue-generating category**.
- Transaction amounts most frequently fall around **200–400 INR**.
- Category-level evaluation reveals which products drive **sales volume vs total revenue**.

---

## 📁 Dataset Used

The dataset contains restaurant transaction records with columns like:

- Transaction ID  
- Transaction Type  
- Food Category  
- Quantity  
- Total Price  
- Timestamp  

---

## 🛠️ Tools & Libraries Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Notebook Execution | Jupyter Notebook / Colab |

---

## 📈 Analysis Conducted

- Missing value inspection
- Duplicate detection
- Summary statistics
- Outlier observation
- Category-wise revenue comparison
- Univariate visualization
- Histogram and bar chart distribution analysis
---

## 📁 Project Structure

```plaintext
EDA_Restuarant_Sales_Trend_Analysis/
│── data/                   # Dataset (optional folder)
│── main.ipynb
│── README.md
```


▶️ How to Run the Notebook

Clone the repository:
```bash
git clone <repo-url>
cd EDA_restaurantSales
```

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

Run the notebook:
```bash
jupyter notebook EDA_restaurantSales.ipynb
```

