Project 2: Exploratory Data Analysis (EDA)
DecodeLabs Industrial Training | Data Analytics | Batch 2026

📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) — the process of analyzing a dataset to understand its structure, patterns, trends, and distributions. Before building any model or report, a data analyst must first explore and understand the data deeply. This project demonstrates that skill using descriptive statistics and visual summaries.

🎯 Goal
Analyze a dataset to understand patterns, trends, and distributions.

✅ Key Requirements

Calculate basic statistics (mean, median, count)
Identify trends and outliers
Summarize key observations


🛠️ Key Skills Used

Data Analysis
Descriptive Statistics
Analytical Thinking


📂 Project Structure
Project2_EDA/
│
├── dataset.xlsx                  # Dataset used for analysis
├── eda_analysis.xlsx             # EDA output with stats and charts
├── screenshots/                  # Screenshots of analysis steps
│   ├── 1_basic_statistics.png
│   ├── 2_trends_identified.png
│   ├── 3_outliers_found.png
│   └── 4_key_observations.png
└── README.md                     # Project documentation

🔍 Steps Performed
Step 1 — Calculate Basic Statistics

Calculated Mean — average value of key numeric columns
Calculated Median — middle value to understand data center
Used Count — to understand volume of data per category
Found Min and Max values across columns

Step 2 — Identify Trends

Analyzed which products generate the most revenue
Identified which time periods had the highest order volume
Observed which referral sources bring the most customers

Step 3 — Identify Outliers

Found unusually high or low order values
Identified orders that were significantly above average price
Flagged any data points that deviate from the normal range

Step 4 — Summarize Key Observations

Documented the most important findings from the dataset
Highlighted patterns that can drive business decisions
Presented a clean summary of insights


📊 Key Observations from the Dataset
MetricValueTotal Orders1,200Total Revenue₹13,64,761.96Average Order Value₹1,053.97Highest Single Order₹3,456.40Lowest Single Order₹100.80Best Selling ProductPrinter (181 orders)Top Revenue ProductChair (₹1,95,620)Top Referral SourceInstagram (259 orders)Most Used PaymentOnline (258 orders)Most Used CouponFREESHIP (313 times)

📈 Trends Identified

Instagram drives the highest number of orders and revenue among all referral sources
Chair and Printer are the top revenue-generating products
Credit Card users have the highest average order value (₹1,127)
Phone has the lowest average order value (₹972) among all products
Orders are fairly evenly distributed across all statuses (Delivered, Shipped, Pending, Cancelled, Returned)


🚨 Outliers Found

Several orders with TotalPrice above ₹3,000 — significantly above the average of ₹1,053
These high-value outliers are mostly Tablet, Laptop, and Monitor orders with Quantity = 5
No negative values or zero values found in price columns


💡 What I Learned

How to calculate and interpret descriptive statistics
How to identify trends by grouping and comparing data
How to spot outliers that could affect analysis
How to summarize data into clear, actionable business insights
The importance of EDA before any deeper analysis or modeling
