# 🛍️ Retail Sales Analytics Project  
Data Cleaning • Exploratory Data Analysis • KPI Reporting • Power BI Dashboard

## 📌 Project Overview  
This project analyzes **retail sales performance** to identify revenue trends, top-performing product categories, customer purchasing patterns, and key business drivers.  
The goal is to help retail stakeholders improve **inventory planning, pricing decisions, marketing strategy, and forecasting accuracy**.

The project demonstrates real-world data analytics steps from **data ingestion → cleaning → EDA → visualization → insights → business recommendations**.

---

## 📂 Repository Structure  
```
Retail_Sales/
│
├── data/                 # Sample or cleaned datasets (no large raw data)
├── notebooks/            # Jupyter notebooks for EDA and data cleaning
├── scripts/              # Python scripts for ETL or reusable functions
├── dashboards/           # Power BI report (.pbix) + screenshots
├── docs/                 # Documentation + images
└── README.md             # Project documentation
```

---

## 🧠 Business Problem  
Retailers need clear insights into **what drives sales**, **who buys**, and **when demand peaks**.  
The company wants to answer:

1. Which products and categories generate the highest revenue?  
2. What seasonal or monthly trends affect sales volume?  
3. Which customer segments spend the most?  
4. How can inventory teams reduce stockouts and overstock?  
5. Which channels perform best?  

This analysis provides **actionable recommendations** to improve sales, optimize inventory, and target high-value customers.

---

## 📊 Dataset Description  
- **Sales transactions** (date, product, price, quantity)  
- **Product details** (category, sub-category, cost, listing price)  
- **Customer information** (customer ID, region, segment)  
- **Store attributes** (location, channel)  

> ⚠️ *Note:* Large or proprietary datasets are not uploaded.  
Small **sample datasets** are included for reproducibility.

---

## 🔧 Tools & Technologies  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **SQL**: PostgreSQL / MySQL / SQL Server  
- **Power BI**: Interactive dashboards  
- **Jupyter Notebook**: Exploratory analysis  
- **Excel**: Additional analysis  

---

## 🧹 Data Cleaning Steps  
Performed in Python + SQL:
- Handling missing values  
- Removing duplicates  
- Converting data types (date, category, numeric)  
- Creating calculated columns (profit, margin, category share)  
- Outlier detection and treatment  
- Merging multiple tables using SQL joins  

---

## 🔍 Exploratory Data Analysis (EDA)

### **1. Sales Trends**
- Monthly and yearly revenue patterns  
- Seasonality spikes  
- Holiday and promotion impacts  

### **2. Product Performance**
- Best-selling categories  
- Profitability analysis  
- Category contribution to total revenue  

### **3. Customer Insights**
- Segmentation by region and customer type  
- Purchase frequency  
- Average order value and lifetime value estimates  

### **4. Store & Channel Performance**
- Online vs in-store comparison  
- Regional revenue breakdown  
- Channel efficiency  

Visualizations include:  
- Time-series charts  
- Heatmaps  
- Bar & pie charts  
- Profit distribution  

---

## 📈 Power BI Dashboard  
The dashboard provides interactive views including:

- **Sales Overview (KPIs, revenue, profit, orders)**  
- **Category & Product Performance**  
- **Regional & Store Analysis**  
- **Customer Segmentation**  
- **Monthly Sales Trends**

Screenshots are included in:  
`docs/screenshots/`

Power BI file located at:  
`dashboards/`

---

## 🚀 How to Run the Project  

### 1. **Clone the repository**
```bash
git clone https://github.com/SriLekya66/Retail_Sales.git
cd Retail_Sales
```

### 2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
```

### 3. **Install dependencies**
```bash
pip install -r requirements.txt
```

### 4. **Run analysis**
- Start Jupyter Notebook:
```bash
jupyter notebook
```
- Open notebooks in the `notebooks/` folder  
- Review ETL/analysis scripts in `scripts/`  
- Open the Power BI file in `dashboards/`  

---

## 💡 Key Insights & Findings  
- **Top-selling categories** contributed X% of total revenue  
- **Region B** achieved the highest sales growth  
- **Online sales** outperformed in-store by X%  
- **Seasonal patterns** show peak demand in ___ months  
- **High-margin items** represent a small portion of the catalog → expansion opportunity  
- **Customer segment C** shows highest lifetime value  



## 📌 Business Recommendations  
- Increase stock for high-demand SKUs to avoid stockouts  
- Promote slow-moving categories with discounts  
- Focus marketing on top customer segments  
- Expand high-margin items to improve profit  
- Strengthen online channel strategy  
- Improve regional forecasting for better distribution  

---

## 📄 License  
This project is licensed under the **MIT License**.

---

## 👩‍💻 Author  
**Sri Lekya Balloli**  
Data Analyst | BI Analyst | Power BI | SQL | Python  
📧 Email: srilekya1108@gmail.com  


---
