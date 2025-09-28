# Swiggy_Orders_Analysis
📖 Project Overview

This project analyzes Swiggy food delivery order data to uncover sales trends, customer behavior, cuisine popularity, and restaurant performance. Using Excel, Python, and Tableau, I developed a dashboard that provides actionable business insights for restaurant owners and Swiggy decision-makers

Swiggy-Orders-Dashboard/
│── data/
│   └── swiggy_orders.csv   # Raw dataset
│   └── cleaned_orders.csv  # Cleaned dataset
│
│── notebooks/
│   └── swiggy_data_cleaning.ipynb   # Python preprocessing
│   └── swiggy_eda.ipynb              # Exploratory Data Analysis
│
│── dashboard/
│   └── Swiggy_Dashboard.twbx   # Tableau packaged workbook
│   └── Swiggy_Dashboard.png    # Snapshot of the dashboard
│
│── README.md

🛠️ Tools & Technologies
-Python (Pandas, Matplotlib, Seaborn) – Data Cleaning & EDA
-Google Sheets – Data validation and preprocessing
-Tableau – Dashboard creation
-SQL – Querying structured insights

📊 Steps Followed
1️⃣ Data Collection
-Dataset includes restaurant orders, cuisine types, prices, ratings, and customer details.

2️⃣ Data Cleaning (Python + Excel)
-Handled missing values.
-Standardized cuisine names.
-Removed duplicate rows.

3️⃣ Exploratory Data Analysis (EDA)
Identified top cuisines by number of orders.
Compared pricing vs customer rating.
Analyzed sales distribution by shift and weekdays.
Segmented customers into repeat vs new buyers.

4️⃣ Dashboard in Tableau
KPIs: Total Orders, Revenue, Avg Order Value.
Filters: Cuisine, Restaurant, Customer Type.

Charts included:
-Bubble chart (Cuisine popularity)
-Scatter plot (Price vs Rating)
-Heatmap (Orders by Day & Shift)
-Line chart (Revenue trend)

📌 Insights Gained
-Indian cuisines had the highest order volume.
-Restaurants with moderate pricing (₹200–₹400) performed better than expensive ones.
-Evening shifts showed the highest order frequency.
-Repeat customers accounted for 65% of revenue, indicating strong loyalty.

🚀 Future Enhancements
-Predict future demand using Time Series Forecasting (ARIMA / Prophet).
-Apply customer segmentation (K-Means clustering) to create targeted marketing strategies.
-Integrate real-time order data for live dashboards.
-Compare multiple food delivery platforms (Swiggy vs Zomato).

Portfolio Website: asitportfolio.lovable.app
