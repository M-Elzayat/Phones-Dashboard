
# 📱 Phone Dashboard

This project presents a detailed **data analysis** and **interactive dashboard** of mobile phone product data using **Excel**, **Python**, **Power BI**, and **DAX**. It focuses on analyzing product pricing, offers, brand behavior, customer ratings, sales volume, and environmental attributes.

---

## 🎯 Project Objective

The main goal is to analyze mobile phone product data from multiple perspectives — **pricing strategies**, **brand competitiveness**, **sales trends**, and **sustainability attributes** — to extract actionable business insights.

---

## 📦 Key Metrics & Insights

### 🛍️ Product-Level Insights

- **Average Product Price:** $176.34  
- **Average Original Price:** $202.15  
- **Average Offer Price:** $176.34  
- **Average Star Rating:** 4.08  
- **Total Units Sold:** 150,000  
- **Total Revenue (Offer Price):** $56,250  
- **Total Revenue (Original Price):** $64,480  

> 🔎 *Insight:* High-selling products are often heavily discounted, leading to lower revenue despite volume.  

---

### 🔄 Offers & Variation Analysis

- **Number of Offers:** 2,695  
- **Products with Variations:** 71.2%  
- **Prime Products:** 88  
- **Amazon’s Choice Products:** 32  
- **Best Seller Products:** 2  
- **Climate-Friendly Products:** 75 (23.5%)

> 📉 *Insight:* The number of promotions per product varies significantly. Only a few products are labeled as “Best Seller” or “Amazon’s Choice”, indicating a potential marketing gap.

---

### 🏷️ Brand-Level Analysis

- **Top Revenue Brand:** Samsung (~$23.8K)  
- **Top Brands by Offers:**  
  - Samsung: 1,159 offers  
  - AT&T: 270  
  - Apple: 234  

> 📊 *Insight:* Samsung leads in both offers and revenue, highlighting its market dominance and extensive product range.

---

### 🌱 Sustainability & Star Rating

- **Climate-Friendly Products:** 75  
- **Average Star Rating:** 4.08  
- **Total Star Rating Sum:** ~408 (based on average * number of products)

> 🌍 *Insight:* Sustainability tags are present in less than a quarter of products, offering an opportunity to expand green product lines.

---

### 📈 Sales Performance

- **Total Sales Volume:** 150K units  
- **Top-Selling Product:** Moto E Play (8K units)  
- **Other High Performers:** Kids’ smartphones, Panasonic models

> 📦 *Insight:* Some niche or low-cost phones significantly outsell premium models, showing value-driven consumer behavior.

---

## 🛠️ Tools & Technologies

| Tool        | Purpose                                         |
|-------------|-------------------------------------------------|
| **Excel**   | Initial data formatting and exploration         |
| **Python**  | Data cleaning and visualization using:  
|             | - `pandas` for transformation  
|             | - `matplotlib`, `seaborn` for EDA               |
| **Power BI**| Dashboard creation and interactivity            |
| **DAX**     | KPIs and calculated measures for performance    |

---

## 🧪 Data Cleaning & Challenges

Key issues resolved during preprocessing:
- Missing values in product attributes and prices  
- Duplicates affecting accuracy of metrics  
- Incorrect data types (e.g., price fields as strings)  
- Inconsistent brand naming (e.g., "Samsung" vs "SAMSUNG")

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Sample EDA snippet
df['product_price'] = pd.to_numeric(df['product_price'], errors='coerce')
sns.histplot(df['product_price'])
plt.title('Price Distribution')
plt.show()
```

---

## 📈 Power BI Dashboard Pages

1. **Home:** Key KPIs & overview  
2. **Average Sales of Phones:** Price, offers, star ratings  
3. **Phones Sales Details:** Sales per product, ratings, price  
4. **Total Sales of Phones:** Brand sales, climate status, total volume  

---

## 📊 DAX Measures Used

- `Average Product Price`  
- `Average Product Original Price`  
- `Average Product Offer Price`  
- `Average Sales Volume`  
- `Average Star Rating`  
- `Number of Offers`  
- `Count_Climate_Friendly`  
- `Sum of Product Price`  
- `Sum of Original Price`  
- `Sum of Star Rating`  
- `Total Sales Volume`

---

## 📂 Folder Structure

```
Phone-dashboard/
├── data/                  # Raw and cleaned dataset
├── python-analysis/       # EDA scripts and charts
├── dashboard/             # Power BI (.pbix) file
└── README.md              # Project documentation
```

---

## 📬 Author

**Mahmoud Mohamed Fawzy Elzayat**  
[🔗 LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)

## License

This project is licensed under the Creative Commons BY-NC-ND 4.0 License.  
© Mahmoud Mohamed Fawzy Elzayat, 2025 — All rights reserved.
