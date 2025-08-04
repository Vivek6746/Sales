# 📊 Sales Dashboard using Superstore Data

## 🛠️ Tools Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Plotly** (optional) – Interactive visualizations
- **Superstore Dataset (CSV)**

---

## 📄 Summary

This project analyzes the Superstore sales data to derive meaningful insights from transactional records. It includes a detailed exploration of sales trends, profitability across segments, geographical analysis, and customer behavior. The final outcome is a clean, well-structured sales dashboard created using Python's visualization libraries.

---

## 🔗 Data Source

- **Dataset**: [Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- File used: `Sample - Superstore.csv`

---

## ✅ Steps Taken

1. **Data Importing**
   - Loaded CSV file using `pandas` with proper encoding handling.

2. **Data Cleaning**
   - Removed duplicates, checked for null values, standardized column names.

3. **Feature Engineering**
   - Extracted order year, month, day for time-series analysis.
   - Calculated profit ratios and discount categories.

4. **Data Analysis**
   - Sales and profit by region, category, and segment.
   - Top-performing states and most profitable segments.
   - Profit vs. discount analysis.

5. **Data Visualization**
   - Created bar plots, line graphs, and pie charts using `matplotlib` and `seaborn`.
   - Optional: Added interactive visualizations using `plotly`.

6. **Dashboard Creation**
   - Combined visualizations into a dashboard format for easy interpretation.

---

## 🎯 Final Outcome

- A Python-powered sales dashboard that shows:
  - Top product categories and sub-categories
  - Regional performance and losses
  - Sales vs. profit analysis
  - Monthly sales trends
  - Customer segments breakdown

---

## 🚀 How to Run

1. Clone or download this repository
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn plotly
