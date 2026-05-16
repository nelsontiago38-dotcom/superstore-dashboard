[README.md](https://github.com/user-attachments/files/27854569/README.md)
# 📊 Interactive Sales Dashboard

**Author:** Nelson Alves  
**Tools:** HTML · CSS · JavaScript · Chart.js · Python  
**Dataset:** [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
**Live Demo:** [View Dashboard](#) ← *(replace with your GitHub Pages link)*

---

## 📌 Project Overview

An interactive business intelligence dashboard built from scratch to analyse 4 years of retail sales data (2014–2017). Designed to replicate the experience of a tool like Google Looker Studio, but fully self-contained in a single HTML file — no frameworks, no backend required.

---

## 🔍 What the Dashboard Shows

| Section | Description |
|--------|-------------|
| **KPI Cards** | Total Revenue, Profit, Margin and Orders — filterable by year |
| **Monthly Trend** | Sales vs Profit line chart across all 48 months |
| **Sales by Category** | Donut chart breaking down revenue by product category |
| **Profit by Region** | Bar chart comparing the 4 sales regions |
| **Profit by Sub-Category** | Ranked horizontal bar chart highlighting winners and loss-makers |
| **Key Insights** | Automated business conclusions drawn from the data |

---

## 💡 Key Findings

- **Technology** is the top revenue category ($869K), with Phones and Copiers as the most profitable sub-categories.
- **Furniture** has the lowest profit margin despite strong sales — Tables and Bookcases consistently operate at a loss, suggesting a discount or pricing problem.
- **2017** was the strongest year in revenue ($693K), with Q3–Q4 showing the highest peaks.
- The **South region** leads in profitability; all regions are positive, but Central shows the tightest margin.

---

## 🛠️ How to Run

No installation needed. Just open the file in any browser:

```bash
# Option 1 — open directly
open sales_dashboard.html

# Option 2 — serve locally
python3 -m http.server 8000
# then go to http://localhost:8000/sales_dashboard.html
```

Or view the live version via GitHub Pages (link above).

---

## 📁 Project Structure

```
superstore-dashboard/
│
├── sales_dashboard.html    # Full dashboard (HTML + CSS + JS in one file)
└── README.md
```

---

## 🔗 Related Project

This dashboard is a companion to my [Superstore Sales Analysis in R](https://github.com/nelson-alves/superstore-sales-analysis), which performs the same analysis using R and ggplot2.

---

*Built as part of my data analytics portfolio. Data sourced from Kaggle's public Superstore dataset.*
