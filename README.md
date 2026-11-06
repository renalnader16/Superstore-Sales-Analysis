# 🛒 Superstore Sales Analysis | Power BI Dashboard

An end-to-end Data Analytics project that analyzes the sales performance of a retail superstore using Microsoft Power BI.

The dashboard covers four areas: overall sales performance, shipping efficiency, product profitability, and customer behavior.

* * *

## 📌 Project Overview

The goal is to understand where the store makes and loses money, how fast it delivers orders, and which products and customers matter most. The dashboard has four pages with navigation buttons and filters for Region, Country, and Year.

## 🎯 Business Objectives

- Track total sales, profit, profit margin, and year-over-year growth.
- Find the top-performing cities and regions.
- Evaluate shipping speed and delays across ship modes.
- Identify the most and least profitable categories and sub-categories.
- Measure the effect of discounts on profit.
- Identify top customers and loss-making customers.

## ❓ Business Questions

1. How have sales and profit changed over the years?
2. Which regions and cities generate the most sales?
3. How quickly are orders shipped, and how many are delayed?
4. Which ship mode is the fastest, and which is the most profitable?
5. Which categories and sub-categories make or lose money?
6. How do discounts affect profit?
7. Who are the top customers by sales and by number of orders?
8. How many customers are loss-making?

* * *

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Measures (Profit Margin %, Sales YoY %, Avg Ship Days, ...) |
| Data Modeling | Organizing the data for analysis |
| Dashboard Design | Page navigation, slicers, consistent layout |

* * *

## 🧹 Data Preparation

- Checked data types and missing values in Power Query.
- Created the **DiscountBand** field to group orders by discount level.
- Prepared date fields (**Year**) for time analysis.
- Created DAX measures for sales, profit, shipping, and customer metrics.

## 🧮 Key DAX Measures

| Measure | Description |
|---------|-------------|
| Total Sales / Total Profit | Overall sales and profit |
| Profit Margin % | Profit ÷ Sales |
| Sales YoY % | Year-over-year sales growth |
| Orders | Number of orders |
| Avg Discount % | Average discount applied |
| Profit on High Discounts | Profit from heavily discounted orders |
| Loss-Making Sales % | Share of sales that lost money |
| Avg Ship Days | Average days between order and shipping |
| % Shipped within 3 Days | Share of orders shipped quickly |
| Same Day Share % | Share of orders shipped the same day |
| Delayed Orders % | Share of delayed orders |
| Customers | Number of unique customers |
| Sales per Customer | Total sales ÷ customers |
| Average Order Value | Total sales ÷ orders |
| Avg Orders per Customer | Orders ÷ customers |
| Loss-Making Customers | Customers with negative total profit |

* * *

## 📊 Dashboard Preview

### Page 1 – Home
![Home](Screenshots/01-home.png)

### Page 2 – Shipping
![Shipping](Screenshots/02-shipping.png)

### Page 3 – Products
![Products](Screenshots/03-products.png)

### Page 4 – Customers
![Customers](Screenshots/04-customers.png)

* * *

## 💡 Key Findings

> ⚠️ Replace each X with the real value from your dashboard, then delete this line
- Total sales are **X** with a profit margin of **X%**.
- Sales grew/declined **X%** year over year.
- **[Region]** is the top region by sales, and **[City]** is the top city.
- **[Category]** is the most profitable category, while **[Sub-Category]** loses money.
- Orders with high discounts generate **X** profit, and **X%** of sales are loss-making.
- **[Ship mode]** is the fastest at **X** days on average, and **X%** of orders ship within 3 days.
- **X** customers are loss-making out of **X** total customers.

## 📈 Business Recommendations

1. **Review discount policy**, especially for sub-categories that lose money under high discounts.
2. **Focus on top regions and cities** while investigating weaker markets.
3. **Improve shipping speed** for the slowest ship mode and reduce delayed orders.
4. **Reward top customers** and encourage repeat orders.
5. **Review loss-making customers** to understand whether discounts or returns drive the loss.

* * *

## 📁 Project Structure

```
Superstore-Sales-Analysis/
├── Screenshots/
├── Superstore_sales_analysis.pbix
└── README.md
```

## 🚀 How to Explore

1. Clone or download this repository.
2. Open `Superstore_sales_analysis.pbix` in Power BI Desktop.
3. Use the page buttons to move between pages.
4. Use the Region, Country, and Year slicers to explore.

## 👩‍💻 Author

**Renal Salah**
- **GitHub:** [renalnader16](https://github.com/renalnader16)
- **LinkedIn:** [Renal Salah](https://linkedin.com/in/renal-salah/)
