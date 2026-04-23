# 🛒 Superstore Sales Analysis

A beginner data analytics project exploring **US retail sales trends, profit margins, and discount impact** using the popular Superstore dataset. Built entirely with Microsoft Excel and Power BI.

---

## 📸 Dashboard Preview

![Superstore Sales Dashboard](/powerbi%20visualization%20picture.png)

> Power BI dashboard showing sales by category, profit trends over time, regional performance, and discount vs profit analysis.

---

## 📁 Project Structure

```
superstore-sales-analysis/
│
├── Sample - Superstore.csv      # Raw dataset (sourced from Kaggle)
├── Superstore_cleaned.xlsx      # Cleaned dataset after preprocessing in Excel
├── dashboard.pbix               # Power BI dashboard file
└── README.md
```

---

## 📌 Key Insights

- 💻 **Technology** generates the highest profit margin despite not having the most orders
- 🪑 **Furniture** has surprisingly low profit despite high sales volume
- 🏷️ **Discounts above 20%** almost always result in negative profit — the business loses money on heavily discounted items
- 🌍 The **West region** outperforms all others in both sales and profit
- 📅 **Q4 (October–December)** shows the biggest sales spike every year — driven by the holiday season

---

## 🧹 Data Cleaning Steps

The raw dataset was cleaned in **Microsoft Excel** before loading into Power BI:

| Step | What Was Done |
|---|---|
| Remove Duplicates | Used Data → Remove Duplicates to check for duplicate rows |
| Format Date Columns | Formatted Order Date and Ship Date as DD/MM/YYYY |
| Added Profit Margin column | Formula: Profit ÷ Sales, formatted as percentage |
| Added Delivery Days column | Formula: Ship Date − Order Date, formatted as number |
| Checked for blank cells | Used Ctrl + G → Special → Blanks to find any missing values |

---

## 📊 Dashboard Visuals

| Visual | Type | What It Shows |
|---|---|---|
| Total Sales | KPI Card | Sum of all sales revenue |
| Total Profit | KPI Card | Sum of all profit |
| Total Orders | KPI Card | Count of all orders |
| Average Profit Margin | KPI Card | Average profit margin % |
| Sales by Category | Bar Chart | Revenue comparison across Furniture, Office Supplies, Technology |
| Sales Over Time | Line Chart | Monthly sales trend across all years |
| Sales by State | Map | Geographic bubble map of sales performance by US state |
| Discount vs Profit | Scatter Chart | Relationship between average discount and profit by sub-category |
| Region Filter | Slicer | Filters all visuals by West, East, Central, South |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning & preprocessing |
| Power BI Desktop | Dashboard & visualisation |
| Kaggle | Data source |

---

## 📂 Dataset

The dataset was sourced from **Kaggle** — Superstore Sales Dataset by vivek468.

It contains ~10,000 rows of US retail orders with the following key fields:

`Order ID` · `Order Date` · `Ship Date` · `Category` · `Sub-Category` · `Sales` · `Profit` · `Discount` · `Quantity` · `Region` · `State` · `City` · `Segment`

🔗 [View Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 🚀 How to View This Project

1. Clone the repository
```bash
git clone https://github.com/jazimahmed/superstore-sales-analysis.git
```
2. Open `Superstore_cleaned.xlsx` in Microsoft Excel to explore the cleaned data
3. Open `dashboard.pbix` in **Power BI Desktop** to interact with the full dashboard

> Power BI Desktop is free — download it at [microsoft.com/power-bi](https://powerbi.microsoft.com/desktop)

---

## 👤 Author

**Jazim Ahmed**
[GitHub](https://github.com/jazimahmed)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).