
# 📊 Sample Sales Data Analysis

A complete sales data analysis and visualization project using **Python (Pandas, Matplotlib, Seaborn)** and **Power BI** to explore trends, identify patterns, and build an interactive dashboard from sample product sales data.

---

## 📁 Dataset

The dataset includes:
- `Sales Person`
- `Country`
- `Product`
- `Date`
- `Amount`
- `Boxes Shipped`

📌 Sample source: `sample-data-10mins.xlsx` (Excel format)

---

## 🧪 Project Objectives

- Analyze sales patterns across products, countries, and time.
- Engineer time-based features for deeper insight.
- Visualize trends using Power BI.
- Build an interactive dashboard for business decision-making.

---

## 📂 Project Structure

```
├── data/
│   └── sample-data-10mins.xlsx
├── enhanced_sales_data.csv
├── sales_analysis.ipynb
├── visuals/
│   └── (plots generated in Python)
├── PowerBI/
│   └── SalesDashboard.pbix
└── README.md
```

---

## 🧰 Tools & Technologies

- **Python 3 (Pandas, Seaborn, Matplotlib)**
- **Jupyter Notebook**
- **Power BI Desktop**
- **Excel**

---

## 📈 Steps Performed

### 1. Data Cleaning & Loading (Python)
- Load data into DataFrame
- Handle missing values and clean formats
- Parse and convert currency values

### 2. Exploratory Data Analysis (EDA)
- Summary stats: mean, median, std, quartiles
- Outlier detection
- Distribution plots and correlation checks

### 3. Feature Engineering
- Extract `hour`, `day`, `month`, `day_of_week` from date
- Add peak/off-peak indicators
- Encode categorical variables

### 4. Power BI Dashboard
- Import enhanced CSV
- Create visuals:
  - Sales by product/country/time
  - Pie chart, funnel, map
  - Histograms, time-series, boxplots
- Add interactivity: filters, slicers, drill-down

---

## 📊 Key Insights

- UK, India, and Australia were top-performing regions.
- “Peanut Butter Cubes” and “99% Dark & Pure” generated the most revenue.
- Sales show seasonal and monthly fluctuations.
- Top-performing salespersons consistently shipped more boxes and had higher sales values.

---

## 📝 Recommendations

- Focus marketing efforts on high-demand products and top countries.
- Analyze and replicate top salesperson strategies.
- Plan inventory and logistics based on monthly trends.

---

## 🔗 How to Run

1. Clone this repo  
```bash
git clone https://github.com/emerick149/sales-data-analysis.git
```

2. Open the `sales_analysis.ipynb` file in Jupyter Notebook  
3. Launch Power BI Desktop and open `Dashboard.pbix` to explore the dashboard.

---

## 📌 Author

**CYIZERE SIBORUREMA Elie**  
  
GitHub: [github.com/emerick149](https://github.com/emerick149/sales-data-analysis)
