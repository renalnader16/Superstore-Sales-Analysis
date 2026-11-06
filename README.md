# 🛒 Superstore Sales Analysis | Power BI Dashboard

An end-to-end Data Analytics project that analyzes the sales performance of a retail superstore using Microsoft Power BI.

The dashboard covers four areas: overall sales performance, shipping efficiency, product profitability, and customer behavior.

* * *

## 📌 Project Overview

The goal is to understand where the store makes and loses money, how fast it delivers orders, and which products and customers matter most. The dashboard has four pages with navigation buttons and filters for Country, Region, and Year.

## 🎯 Business Objectives

- Track total sales, profit, profit margin, and order volume.
- Find the top-performing cities and regions.
- Evaluate shipping speed and delays across ship modes.
- Identify the most and least profitable categories and sub-categories.
- Measure the effect of discounts on profit.
- Identify top customers and loss-making customers.

## ❓ Business Questions

1. How have sales changed over the years?
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
| DAX | Measures (Profit Margin %, Avg Ship Days, Loss-Making Sales %, ...) |
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
| Orders | Number of orders |
| Avg Discount % | Average discount applied |
| Profit on High Discounts | Profit from heavily discounted orders |
| Loss-Making Sales % | Share of sales that lost money |
| Avg Ship Days | Average days to ship an order |
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
![Home](Screenshots/Screenshot%202026-10-25%20184306.png)

### Page 2 – Shipping
![Shipping](Screenshots/Screenshot%202026-10-25%20184442.png)

### Page 3 – Products
![Products](Screenshots/Screenshot%202026-10-25%20184100.png)

### Page 4 – Customers
![Customers](Screenshots/Screenshot%202026-10-25%20184506.png)

* * *

## 💡 Key Findings

- Total sales are **2.8M** with a profit of **389K** (profit margin **13.7%**) across about **5K orders**.
- Sales grew every year, from **0.51M in 2021** to **0.95M in 2024**.
- **West** is the top region (**34.77%** of sales). **New York City** (279K) and **Los Angeles** (266K) are the top cities.
- **Technology** is the strongest category (1.19M sales, 0.22M profit). **Furniture** has high sales (1.06M) but only 0.04M profit.
- **Copiers** (95K) and **Phones** (74K) are the most profitable sub-categories, while **Tables** (-23K), **Bookcases** (-8K), and **Supplies** (-2K) lose money.
- **Discounts hurt profit.** Orders with no discount have a **30.0%** margin, while orders with 21–40% discount have **-13.8%** and 41–80% have **-53.1%**. High discounts cost **127K** in profit, and **21.0%** of sales are loss-making.
- Average shipping time is **4.2 days**, and only **32.3%** of orders ship within 3 days. **Standard Class** is 59% of orders and takes **5.4 days**, while First Class takes 2.0 days.
- The store has **663 customers** with an average of **7.4 orders** each. **107 customers** are loss-making.
- **George White** is the top customer by sales (**56K**), more than double the next one.

## 📈 Business Recommendations

1. **Cap discounts at 20%.** Orders above that level lose money on average.
2. **Review Tables, Bookcases, and Supplies** for pricing or cost problems.
3. **Improve Standard Class delivery time**, since it carries most of the orders.
4. **Protect top customers** like George White, and review the 107 loss-making customers.
5. **Build on Technology products** and the West region, the strongest sources of sales and profit.

* * *

## 📁 Project Structure

```
Superstore-Sales-Analysis/
├── Screenshots/
├── Superstore sales analysis.pbix
└── README.md
```

## 🚀 How to Explore

1. Clone or download this repository.
2. Open `Superstore sales analysis.pbix` in Power BI Desktop.
3. Use the page buttons to move between pages.
4. Use the Country, Region, and Year slicers to explore.

## 👩‍💻 Author

**Renal Salah**
- **GitHub:** [renalnader16](https://github.com/renalnader16)
- **LinkedIn:** [Renal Salah](https://linkedin.com/in/renal-salah/)
