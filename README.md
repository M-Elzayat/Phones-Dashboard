# 📱 Phone Dashboard

This project presents a detailed **data analysis** and **interactive dashboard** of mobile phone product data using **Excel**, **Python**, **Power BI**, and **DAX**. It focuses on analyzing product pricing, offers, brand behavior, customer ratings, sales volume, and environmental attributes.

## 🎯 Project Objective

This project aims to analyze mobile phone product data from multiple perspectives, including pricing, brand dynamics, sales performance, and environmental impact. Key insights include:

### 📦 Product-Level Insights

- Average Product Price  
- Average Product Original Price  
- Average Product Offer Price  
- Average Star Rating  
- Average Sales Volume  
- Average Price and Rating per Product  
- Sales Volume and Average Rating per Product  
- Price per Product  
- Sum of Product Price  
- Sum of Product Original Price

### 🔄 Offer & Variation Analysis

- Number of Offers  
- Total Offers per Product  
- Comparison of Original and Discounted Prices by Product  
- Average Original Price vs. Offer Price  
- Number of Products With and Without Variations  
- Number of Prime vs. Non-Prime Products  
- Number of Amazon’s Choice vs. Other Products  
- Number of Best Seller vs. Worst Seller Products  

### 🏷️ Brand-Level Analysis

- Brand-wise Comparison of Original and Offer Prices  
- Number of Offers by Brand Name  
- Sum of Product Price by Brand Name  

### 🌱 Sustainability & Rating

- Count of Products by Climate-Friendly Status  
- Number of Climate-Friendly Products  
- Average Star Rating  
- Sum of Star Rating  

### 📊 Sales Performance

- Total Sales Volume  
- Sum of Sales Volume by Product Title

## 🛠️ Tools & Technologies

| Tool        | Purpose                                         |
|-------------|-------------------------------------------------|
| Excel       | Initial data formatting and exploration         |
| Python      | Data cleaning and visualization using:  
|             | - `pandas`: cleaning, transformation  
|             | - `matplotlib`, `seaborn`: visual exploration   |
| Power BI    | Dashboard creation and interactivity            |
| DAX         | KPIs and custom calculations for insights       |

## 🧪 Data Cleaning & Challenges

During preprocessing, the following issues were addressed:
- **Missing values** in product details and pricing  
- **Duplicate rows** affecting accurate counts  
- **Incorrect data types** (e.g., price columns as text)  
- **Inconsistent brand names or classifications**

The dashboard includes four interactive pages:

Home – Project overview and key metrics

Average Sales of Phones – Offer analysis, pricing comparison, and ratings

Phones Sales Details – Individual product details and comparisons

Total Sales of Phones – Summary of sales, environmental metrics, and brand behavior

📌 DAX Measures Used
The following measures were created in Power BI:

Average Product Price

Average Product Original Price

Avreage Product Offer Price

Average Sales Volume

Average Star Rating

Count_Climate_Friendly

Number of Offers

Sum of product price

Sum of product Orignal Price

Sum of Star Rating

Total Sales Volume

phone-dashboard/
├── data/                  # Raw and cleaned datasets
├── python-analysis/       # EDA scripts and visuals
├── dashboard/             # Power BI (.pbix) file
├── visuals/               # Screenshots of dashboard pages
└── README.md              # Project documentation
📬 Author
Mahmoud Mohamed Fawzy Elzayat
🔗 LinkedIn
