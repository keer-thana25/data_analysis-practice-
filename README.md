# 📊 Customer Data Analysis & 🛒 Amazon Web Scraping Project

## 📌 Project Overview

This project consists of two main components:

1. Customer Data Analysis using Python
2. Amazon Product Data Web Scraping

The project demonstrates data collection, cleaning, visualization, and analysis using Python libraries.

---

## 📁 Project Structure

```
Project Folder
│── data_analysis.py
│── amazon_scraping.py
│── Practice-Datasets.csv
│── README.md
```

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Requests
- BeautifulSoup

---

# 📊 Part 1: Customer Data Analysis

## 📁 Dataset

File: `Practice-Datasets.csv`

### Dataset Columns:

- Customer_ID  
- Age  
- Gender  
- City  
- Monthly_Income  
- Spending_Score  
- Purchase_Amount  
- Product_Category  
- Purchase_Date  

---

## 📈 Analysis Performed

- Histogram of Age distribution
- Pie chart of Gender distribution
- Bar chart of customers by City
- Box plot of Monthly Income
- Spending Score distribution
- Purchase Amount trend over time
- Monthly Purchase aggregation
- Product Category distribution
- Income vs Spending Score scatter plot
- Age vs Purchase Amount analysis
- Category-wise Purchase comparison

---

## 🎯 Key Insights

- Spending score varies across cities.
- Some product categories generate higher revenue.
- Monthly income impacts spending behavior.
- Purchase amounts show monthly variation trends.

---

# 🛒 Part 2: Amazon Web Scraping

## 📌 Objective

To scrape Amazon product data including:

- Product Name
- Price
- Rating
- Number of Reviews

---

## 🔎 Process

1. Send HTTP request to Amazon page
2. Parse HTML using BeautifulSoup
3. Extract product details
4. Store data into CSV
5. Perform basic analysis

---

## ▶️ How to Run

### Install Required Libraries

```bash
pip install pandas matplotlib seaborn requests beautifulsoup4
```

### Run Data Analysis

```bash
python data_analysis.py
```

### Run Web Scraping

```bash
python amazon_scraping.py
```

---

## 📌 Conclusion

This project demonstrates:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Web Scraping
- CSV Data Handling
- Insight Extraction

---

