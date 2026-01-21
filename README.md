# 📊 E-Commerce Sales Performance & Customer Segmentation

An end-to-end **data analytics and data storytelling project** focused on analyzing e-commerce sales performance and customer behavior using **RFM (Recency, Frequency, Monetary) segmentation**.  
This project delivers **actionable business insights** through structured analysis and visual dashboards.

---

## 🎯 Project Objectives
- Evaluate overall sales performance
- Identify revenue trends and seasonality
- Analyze best-selling products
- Understand customer purchase behavior
- Segment customers using RFM analysis
- Provide strategic business recommendations

---

## 📂 Project Structure
Project3_EcommerceAnalysis/
│
├── data/
│ ├── raw/
│ │ └── data.csv
│ └── processed/
│ ├── ecommerce_cleaned.csv
│ └── rfm_segmentation.csv
│
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_sales_analysis.ipynb
│ └── 03_customer_segmentation_rfm.ipynb
│
├── visuals/
│ └── charts/
│ ├── monthly_revenue.png
│ ├── top_products.png
│ ├── purchase_frequency.png
│ ├── rfm_segment_distribution.png
│ └── rfm_heatmap.png
│
├── dashboards/
│ ├── monthly_revenue_dashboard.png
│ ├── top_products_dashboard.png
│ └── rfm_segments_dashboard.png
│
├── reports/
│ └── Ecommerce_Insights_Report.md
│
├── README.md
└── requirements.txt


---

## 📊 Dataset
- **Source:** Kaggle – E-commerce Transactions Dataset
- **Key Fields:**
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country

---

## 🔍 Analysis Workflow

### 1️⃣ Data Preprocessing
- Removed cancelled transactions
- Handled missing customer IDs
- Removed invalid quantities and prices
- Created revenue feature
- Saved cleaned dataset for analysis

### 2️⃣ Sales Performance Analysis
- Monthly revenue trend analysis
- Identification of seasonal patterns
- Top-selling products by revenue
- Customer purchase frequency analysis

### 3️⃣ Customer Segmentation (RFM)
- **Recency:** Days since last purchase
- **Frequency:** Number of transactions
- **Monetary:** Total customer revenue
- Customers segmented into:
  - Champions
  - Loyal Customers
  - Potential Loyalists
  - At-Risk Customers
  - Others

---

## 📈 Dashboards

### Monthly Revenue Trend
![Monthly Revenue](dashboards/monthly_revenue_dashboard.png)

### Top Selling Products
![Top Products](dashboards/top_products_dashboard.png)

### RFM Customer Segmentation
![RFM Segments](dashboards/rfm_segments_dashboard.png)

---

## 📑 Key Business Insights
- Sales show strong **seasonality**, peaking during end-of-year months
- A small percentage of products generate the majority of revenue
- Repeat customers contribute significantly higher lifetime value
- At-risk customers represent an opportunity for re-engagement campaigns

---

## 📌 Business Recommendations
- Focus on retention strategies for high-value customers
- Introduce loyalty and reward programs
- Optimize inventory for top-performing products
- Run targeted campaigns during peak sales periods
- Use RFM segmentation for personalized marketing

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 💼 Resume Highlight
> Built an end-to-end e-commerce analytics project with RFM-based customer segmentation, sales performance analysis, and dashboard visualizations to deliver actionable business insights.

---

## ✅ Project Status
✔ Completed  
✔ Fully documented  
✔ GitHub-ready  
✔ Resume-ready  

---

⭐ If you find this project useful, feel free to star the repository!
