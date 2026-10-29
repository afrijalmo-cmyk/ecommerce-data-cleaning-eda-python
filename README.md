# E-Commerce Profitability & Shipping Analysis | Python

## 📌 Overview
Analyzed 51,275 E-commerce transactions to identify profitability issues and shipping inefficiency. Built as part of Certified Data Analyst (BNSP - DQLab), now transitioning to Data Scientist at Digital Skola.

Dataset: 51,282 -> 51,275 rows after cleaning (5 duplicates, 7 missing)
Tools: Python (Pandas, NumPy, Matplotlib, Seaborn)

## 🔍 Process
1. Data Cleaning: Missing values, duplicates, datetime conversion
2. Feature Engineering: Shipping Days = Ship Date - Order Date, Order Year/Month/Weekday
3. Anomaly Detection: Found Shipping Days -106 and filtered to df_clean
4. EDA: Sales-Profit correlation 0.92, Discount-Profit -0.12, found lowest profit product Mixer/Juicer $0.5

## 💡 Business Recommendation
- Review Electronic Category pricing (high sales, near-zero profit)
- Evaluate discount strategy
- Audit shipping process for anomaly

## 👨‍💻 Author
## 👨‍💻 Penulis

**APRIJAL, S.E** | Certified Data Analyst (BNSP) DQLab | Aspiring Data Scientist @ Digital Skola  
🔗 Colab: https://colab.research.google.com/drive/1W3tNRbfX0saYZHYzlWTfWrf9hIrM2Myw  
🔗 LinkedIn: [https://www.linkedin.com/in/aprijal-s-e-a76ba2318/]
