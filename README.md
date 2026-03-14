# 🌍 Global Superstore Sales Analysis Dashboard

> **Where is the business making money — and where is it leaking it?**  
> This Power BI dashboard analyzes global retail performance across categories, regions, customers, and time to surface actionable sales and profitability insights.

---

## 🧩 Problem Statement

Retail businesses operating globally face a critical challenge: **sales volume doesn't always equal profitability.** A region or product category can look successful on the surface while quietly underperforming on margins. This project analyzes the Global Superstore dataset to answer:

- Which categories and regions drive the most profit — not just sales?
- Who are the highest-value customers?
- Where are the hidden inefficiencies in the business?

---

## 📊 Dashboard Overview

Built in **Power BI**, the dashboard delivers an executive-level view of business performance with interactive filters across Region, Segment, Category, and Ship Mode.

![Dashboard Preview](dashboard_preview.png)

---

## 📈 Key Metrics at a Glance

| Metric | Value |
|---|---|
| **Total Sales** | $12.64M |
| **Total Profit** | $1.47M |
| **Total Orders** | 25,000 |
| **Profit Margin** | 11.61% |

---

## 🔑 Key Findings

| Insight | Detail |
|---|---|
| **Top Category by Sales** | Technology — $4.7M, followed by Furniture ($4.1M) and Office Supplies ($3.8M) |
| **Most Profitable Region** | Central — $0.31M profit, nearly double the next region (North at $0.19M) |
| **Lowest Performing Regions** | Canada ($0.02M) and Southeast Asia ($0.04M) — high sales, low returns |
| **Most Profitable Sub-Categories** | Copiers and Phones lead profit by a wide margin |
| **Top Customer** | Tom Ashbrook — $40K in sales |
| **Sales Trend** | Gradual decline in order volume over time — signals potential market saturation or retention issue |

---

## 💡 Business Recommendations

1. **Double down on Technology** — It leads in both sales and profitability. Expanding the technology product range or running targeted promotions could yield strong ROI.

2. **Investigate Canada and Southeast Asia** — These regions show disproportionately low profit relative to orders. A pricing, shipping cost, or product mix issue likely exists and needs review.

3. **Prioritize Copiers and Phones** — These sub-categories drive the most profit. Ensuring consistent stock and strong marketing here directly impacts the bottom line.

4. **Address the declining sales trend** — The Sales Trend Over Time chart shows a downward slope. A customer retention or re-engagement strategy should be explored.

5. **Focus on top customers** — The top 10 customers account for a significant revenue share. A VIP loyalty or account management program could protect and grow this segment.

---

## 🛠️ Tools & Technologies

- **Power BI** — Interactive dashboard design
- **DAX** — Custom measures for profit margin, aggregations, and rankings
- **Power Query** — Data cleaning and transformation
- **Dataset** — Global Superstore Dataset (Kaggle)

---

## 📁 Project Structure

```
global-superstore-sales-analysis-powerbi/
│
├── GlobalSuperstore.pbix       # Power BI dashboard file
├── dashboard_preview.png       # Dashboard screenshot
├── Global_Superstore2.csv      # Raw dataset
└── README.md                   # Project documentation
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop** (free to download)
3. Use the filter panel on the right to slice by Region, Segment, Category, and Ship Mode
4. Hover over charts for detailed tooltips and drill-through insights

---

## 🔮 Future Improvements

- Add a **Year-over-Year (YoY) growth comparison** page to track performance trends more clearly
- Build a **profitability heatmap by country** for deeper geographic analysis
- Incorporate **forecasting visuals** using Power BI's built-in analytics to project future sales
- Add **return rate data** to understand which products hurt margins through refunds

---

## 👤 Author

**Madhusmita Jena** — MCA Student | Aspiring Data Analyst  
📧 madhusmitajena2501@gmail.com | 🐙 [GitHub Profile](https://github.com/Madhu-j25)
