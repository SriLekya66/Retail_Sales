# 🛍️ Retail Sales Analytics Project  
Data Cleaning • Exploratory Data Analysis • KPI Reporting • Power BI Dashboard

## 📌 Project Overview  
This project analyzes **retail sales performance** to identify revenue trends, top‑performing product categories, customer purchasing patterns, and key business drivers.  
The goal is to help retail stakeholders improve **inventory planning, pricing decisions, marketing strategy, and forecasting accuracy**.

---

## 📂 Repository Structure  
```
Retail_Sales/
├── data/                 # Sample or cleaned datasets
├── notebooks/            # Jupyter notebooks for EDA and data cleaning
├── scripts/              # Python scripts for ETL / data processing
├── dashboards/           # Power BI files or screenshot exports
├── docs/                 # Documentation, screenshots
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
└── LICENSE               # Project license
```

---

## 🧠 Business Problem  
Retailers need actionable insights into:

1. Which products and categories generate the highest revenue?  
2. What are the seasonal or monthly trends in demand?  
3. Which customer segments contribute the most to sales?  
4. How can inventory teams minimize stockouts and overstock?  
5. Which sales channels (online, in-store) are performing best?

This analysis is aligned to help business teams make data‑driven decisions and optimize operations.

---

## 📊 Dataset Description  
- **Sales transactions** — date, product ID, quantity, price  
- **Product information** — category, sub-category, cost, price  
- **Customer details** — customer ID, region, segment  
- **Store/channel attributes** — store location, channel type (online / physical)  

> ⚠️ *Note:* Full raw dataset is not included due to size / licensing. A small sample is provided to reproduce key analyses.

---

## 🔧 Tools & Technologies  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **SQL**: (e.g., PostgreSQL or MySQL) for data queries  
- **Jupyter Notebook**: For exploration and analysis  
- **Power BI**: For visual dashboards  
- **Excel**: Supplemental exploratory or summary work  

---

## 🧹 Data Cleaning Steps  
Performed using Python and SQL:  
- Impute or drop missing values  
- Remove duplicate records  
- Convert data types (dates, categorical)  
- Create derived metrics (profit, margin, YoY growth, etc.)  
- Identify and handle outliers  
- Merge tables using SQL joins  

---

## 🔍 Exploratory Data Analysis (EDA)  
**1. Sales Trends**  
- Monthly and yearly revenue trends  
- Seasonal peaks (promotions, holidays)  

**2. Product Performance**  
- Revenue by category  
- Profit margin analysis  
- Top SKUs by sales & profitability  

**3. Customer Insights**  
- Customer segmentation (by region, loyalty, spending)  
- Purchase frequency, average order value  

**4. Channel / Store Analysis**  
- Online vs in-store performance  
- Regional comparisons  

Visualization types: time-series charts, heatmaps, bar/pie charts, profit distributions

---

## 📈 Power BI Dashboard  
Includes:  
- KPI Overview (Revenue, Orders, Profit)  
- Category & Product Performance  
- Customer Segment Insights  
- Region / Store-level Performance  
- Monthly Sales Trends

**Screenshots** (if available) are stored in: `docs/screenshots/`  
**Power BI file** (if included) is in: `dashboards/`

---

## 🚀 How to Run the Project  

### 1. Clone the repository  
```bash
git clone https://github.com/SriLekya66/Retail_Sales.git  
cd Retail_Sales
```

### 2. Create a Python virtual environment  
```bash
python -m venv venv  
source venv/bin/activate   # Mac / Linux  
venv\Scripts\activate      # Windows
```

### 3. Install dependencies  
```bash
pip install -r requirements.txt
```

### 4. Run the analysis  
- Start Jupyter Notebook:  
```bash
jupyter notebook
```  
- Open and run the notebooks under `notebooks/`  
- Use Python scripts in `scripts/` as needed  
- Open Power BI file in `dashboards/` to view or export dashboards  

---

## 💡 Key Insights & Findings  
*(Replace these with your actual results)*  
- Top-selling categories contributed X% of total revenue  
- Region B saw the highest YoY growth of Y%  
- Online sales outperformed in-store by Z%  
- Seasonal peaks identified in Month1, Month2  
- High-margin SKUs represent a small portion of sales but contribute W% of profit  
- Customer segment C shows highest lifetime value  

---

## 📌 Business Recommendations  
- Prioritize inventory for high-demand SKUs to reduce stockouts  
- Run promotions during off-peak months  
- Focus marketing on high-value customer segments  
- Expand high-margin product lines  
- Strengthen online channel strategy  
- Use region-based forecasting to optimize inventory and distribution  

---

## 📄 License  
This project is licensed under the **MIT License**.

---

## 👩‍💻 Author  
**Sri Lekya Balloli**  
Data Analyst | BI Analyst | Python | Power BI  
📧 Email: srilekya1108@gmail.com  
🔗 LinkedIn: *Add your LinkedIn link here*
