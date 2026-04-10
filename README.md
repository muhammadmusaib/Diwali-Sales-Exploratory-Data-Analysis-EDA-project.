# 🎆 Diwali Sales Analysis

> A data analysis project exploring customer purchasing behavior, top product categories, and revenue-driving factors from Diwali sales data.

---

## 📖 Project Overview

This project analyzes **Diwali sales data** to uncover actionable business insights. By exploring customer demographics, product categories, and regional patterns, the analysis helps businesses improve their marketing and sales strategies for festive seasons.

---

## 🎯 Objectives

- Understand customer demographics and purchasing behavior
- Identify top-performing product categories
- Analyze revenue and order trends
- Discover patterns based on gender, age, marital status, occupation, and geography

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 🐼 Pandas | Data manipulation and analysis |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical data visualization |
| 📓 Jupyter Notebook | Interactive analysis environment |

---

## 📂 Dataset Description

**File:** `Diwali Sales Data.csv`

| Column | Description |
|--------|-------------|
| `User_ID` | Unique customer identifier |
| `Cust_name` | Customer name |
| `Product_ID` | Unique product identifier |
| `Gender` | Customer gender (M/F) |
| `Age Group` | Customer age group (e.g., 26-35) |
| `Age` | Customer age |
| `Marital_Status` | 0 = Unmarried, 1 = Married |
| `State` | Indian state |
| `Zone` | Geographic zone (Central, Eastern, etc.) |
| `Occupation` | Customer's profession |
| `Product_Category` | Category of the purchased product |
| `Orders` | Number of orders placed |
| `Amount` | Total amount spent (₹) |

---

## 📊 Key Questions Answered

| # | Question | Insight |
|---|---------|---------|
| 1 | Total revenue & orders? | Overall business performance snapshot |
| 2 | Which gender + age group drives most revenue? | Targeted marketing segments |
| 3 | Do married customers spend more? | Family-oriented buying behavior |
| 4 | Top 5 states by revenue? | Regional marketing focus |
| 5 | Which zone leads in revenue & orders? | Geographic revenue distribution |
| 6 | Which occupation group spends the most? | Premium customer targeting |
| 7 | Revenue vs. orders by product category? | High Revenue ≠ High Demand |
| 8 | Average Order Value (AOV) by gender? | Spending behavior insights |
| 9 | Top 10 customers by total spending? | Loyalty program candidates |
| 10 | Which state + category combo drives most revenue? | Hyper-targeted regional strategy |

---

## 💡 Key Takeaways

- 🎯 **Target Audience:** Age group **26–35** is the primary buyer segment
- 👩 **Gender Contribution:** Female customers are major revenue contributors
- 💍 **Marital Status:** Married customers tend to spend more
- 🗺️ **Regional Insights:** Certain states dominate sales — useful for logistics & marketing
- 🛒 **Pricing Insight:** High revenue categories ≠ high demand — pricing strategy matters

---

## 🚀 How to Run

1. Clone or download this repository
2. Make sure you have the following installed:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Place `Diwali Sales Data.csv` in the same directory as the notebook
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Diwali_sales_analysis.ipynb
   ```
5. Run all cells (Kernel → Restart & Run All)

---

## 📌 Future Improvements

- [ ] Add predictive analysis (sales forecasting)
- [ ] Build an interactive dashboard (Power BI / Tableau)
- [ ] Perform customer segmentation using clustering (K-Means)
- [ ] Time-series analysis if date data becomes available

---

## 🙌 Author

**Mohd. Musaib Khan**  
Aspiring Data Analyst | Frontend Developer

---

*Feel free to fork this project, raise issues, or suggest improvements!*
