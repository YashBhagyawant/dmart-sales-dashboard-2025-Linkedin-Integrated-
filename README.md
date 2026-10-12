# 🛒 DMart Retail Sales Dashboard 2025

End-to-end DMart 2025 retail analytics project: data extraction, data cleaning and data manipulation on 2,500 transactions, followed by descriptive analysis, KPI tracking and interactive dashboard building using Excel, HTML, CSS and JavaScript. Features cross-filtering charts, sales, profit and margin insights.

> ⚠️ **Note:** The dataset is synthetic practice data. It is **not** actual or confidential DMart sales data.

---

## 📊 Dashboard

![DMart Dashboard]<img width="1875" height="891" alt="Front page" src="https://github.com/user-attachments/assets/b76df173-6d2d-4725-af75-ff30a59c0f4d" />
)

### 📍 Cities Covered
| State | Cities |
|---|---|
| Maharashtra | Mumbai, Navi Mumbai, Thane, Pune, Nagpur, Nashik |
| Gujarat | Ahmedabad, Surat |
| Telangana | Hyderabad |
| Karnataka | Bengaluru |

### 📈 Visuals Included
- **Monthly Net Sales:** bar chart with a profit trend line (Jan–Dec 2025)
- **Sales Channel:** donut chart (In-Store vs Online)
- **By Product Category:** horizontal bars with a Sales / Profit / Qty toggle (11 categories)
- **By City:** horizontal bar ranking across all 10 cities
- **Payment Mode:** donut chart (Cash, UPI, Wallet, Debit Card, Credit Card)
- **Customer Segment:** donut chart (Regular, Member, Premium)
- **Order Status:** donut chart (Completed, Returned, Cancelled)
- **Top 8 Products:** table with units, net sales and profit

---

## 🎛️ Slicers & KPI Cards

![Slicers and KPI Cards](<img width="1880" height="895" alt="Slicer and city name" src="https://github.com/user-attachments/assets/975acdbf-589a-4d18-9108-cbe0bb58b9cf" />
)

**Slicers (filters):** City · Category · Channel · Segment · Status · Month, plus a Reset button. Every chart, KPI and table updates instantly, and clicking any bar, slice or month cross-filters the whole dashboard.

**KPI cards:**
| KPI | Meaning |
|---|---|
| Net Sales | Total sales after discounts (₹) |
| Est. Profit | Estimated profit (₹) |
| Profit Margin | Profit ÷ Net Sales (%) |
| Transactions | Number of orders |
| Units Sold | Total quantity sold |
| Avg Order Value | Net Sales ÷ Transactions |

---

## 🔄 Project Workflow
1. **Data extraction:** loaded 2,500 simulated retail transactions (01-Jan-2025 to 31-Dec-2025)
2. **Data cleaning & validation:** checked duplicates, missing values and data types, and produced a Data Quality Report
3. **Data manipulation:** created Month, Year, Net Sales, Estimated Profit and Profit Margin % fields
4. **Outlier handling:** box-and-whisker analysis, with values capped using the 1.5×IQR upper fence (winsorizing)
5. **Descriptive analysis:** count, min, quartiles, mean, max and standard deviation
6. **Pivot tables, KPIs & slicers:** Excel analysis by month, category, city and more
7. **Dashboard building:** interactive dashboard in a single HTML file (HTML + CSS + JavaScript)

## 🛠️ Tech Stack
`Excel` · `Pivot Tables` · `Slicers` · `HTML5` · `CSS3` · `JavaScript` · `SVG`

## 📁 Repository Structure
```
├── index.html                  # Interactive dashboard (HTML + CSS + JS in one file)
├── data/
│   └── Dmart_dashboard_YSB.xlsx   # Excel workbook (Clean Data, Pivots, KPIs, etc.)
├── images/
│   ├── Front_page.png
│   └── Slicer_and_city_name.png
└── README.md
```

## 🚀 How to Run
1. Download or clone the repository.
2. Open `index.html` in any browser. No installation or internet connection is needed.

> To publish it online, enable **GitHub Pages** (Settings → Pages → Deploy from the `main` branch).

---

## 👤 Author
**Yash Sandeep Bhagyawant**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yb2654)
