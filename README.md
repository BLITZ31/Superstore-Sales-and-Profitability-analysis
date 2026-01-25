# Superstore-Sales-and-Profitability-analysis

![Power BI Dashboard Preview](dashboard/dashboard preview/Screenshot 2026-01-23 213232.png)

An end-to-end data analysis project using **Python (Pandas/Seaborn)** for Exploratory Data Analysis (EDA) and **Power BI** for interactive business intelligence. This project identifies key drivers of "Capital" efficiency and the impact of discount strategies on the bottom line.

---

### 📊 Executive Summary
The goal of this analysis was to determine how product categories and discounting strategies affect overall profitability. By analyzing ~10,000 rows of retail data, I identified critical **"Loss Leaders"** and high-performing **"Signature Products"** to guide inventory and pricing decisions.

---

### 💡 Key Business Insights
* **The Discount Trap**: Analysis proves a strong negative correlation between high discounts and profit. A **10% discount** was identified as the "optimal" threshold; anything beyond this leads to a sharp decline in median profit.
* **The "Table" Problem**: Despite generating high sales, the **Tables** sub-category is the biggest source of loss for the business.
* **Volume vs. Value**: While **Technology** is the profit engine, **Office Supplies** drive the highest volume (60.3% of total quantity), with **Binders** identified as a "Signature Product" due to high volume and strong capital contribution.
* **Seasonality**: Sales consistently peak during the **Q4 festive season** (November/December), suggesting a need for increased inventory prep in early Q4.

---

### 🛠️ Tech Stack
* **Python 3.14**: Data cleaning and initial EDA.
* **Pandas**: Data manipulation and handling encoding issues (ISO-8859-1/Latin-1).
* **Seaborn/Matplotlib**: Correlation heatmaps and statistical visualizations.
* **Power BI**: Interactive dashboarding, DAX modeling, and visual storytelling.

---

### 📂 Project Structure
```text
├── dashboard/
│   └── Dashboard Preview                       #static view of Power BI Dashboard
│         └──Screenshot 2026-01-23 213232       #Sales($)
│         └──Screenshot 2026-01-23 213245       #Sales(volume)
│   └── superstore_v1.pbix                      #Interactive dasboard
├──  Data/
│   └── Superstore_sales_data.csv               # Raw dataset (Latin-1 encoded)
├── Notebook/
│   └── Sales.ipynb                             # Python EDA & Visualization               
├── requirements.txt                            # Dependencies (pandas, seaborn, etc.)
└── README.md                                   # Project documentation

