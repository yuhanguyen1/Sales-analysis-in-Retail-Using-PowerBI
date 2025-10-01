# 🛒 Sales Analysis in Retail Using Power BI | Global Superstore  

<img width="600" height="417" alt="Retail-Marketing-là-gì-và-trong-thực-thế-nó-như-nào" src="https://github.com/user-attachments/assets/d2493e88-1867-495a-a809-7b67ddc17319" />


**Author:** Nguyễn Anh Huy  
**Date:** August 2025  
**Tools Used:** Power BI, DAX, Data Modeling  

---

## 📑 Table of Contents  
- 📌 [Background & Overview](#-background--overview)  
- 📂 [Dataset Description & Data Structure](#-dataset-description--data-structure)  
- 🧠 [Design Thinking Process](#-design-thinking-process)  
- 📊 [Key Insights & Visualizations](#-key-insights--visualizations)  
- 🔎 [Final Conclusion & Recommendation](#-final-conclusion--recommendation)  

---

## 📌 Background & Overview  

### 🎯 Objective  
This project delivers a **Power BI dashboard** built on the **Global Superstore dataset**, aimed at providing **senior managers** with clear, data-driven insights into:  
- Retail sales performance across regions and product categories  
- Market expansion opportunities with the highest ROI  
- Customer and product strategies to sustain growth  
- Operational efficiency across shipping, returns, and customer retention  

### 👤 Who is this project for?  
✔️ Senior managers & executives needing strategic market insights  
✔️ Data analysts & business analysts focusing on retail analytics  
✔️ Marketing & sales teams targeting product and customer growth  
✔️ Operations leaders optimizing shipping efficiency and returns  

### ❓ Key Business Questions  
- What is the current **sales and profit performance** of Superstore?  
- Which **markets and customer segments** drive the most revenue & margin?  
- Which **products and categories** should be prioritized for growth?  
- How can **shipping and operations** be optimized to reduce costs & returns?  

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- **Source:** Global Superstore dataset (Kaggle)  
- **Size:** ~51,000+ records  
- **Format:** CSV  

### 📊 Data Tables  
1. **Orders** – Transaction & customer details (~51K records)  
2. **Returns** – Returned orders log  
3. **People** – Sales representatives by region  

### 🔗 Data Relationships  
| From Table | To Table | Join Key | Relationship Type |  
|------------|----------|----------|------------------|  
| Orders     | People   | Region   | Many-to-One      |  
| Orders     | Returns  | Order ID | One-to-One (Left Join) |  

---

## 🧠 Design Thinking Process  

1️⃣ **Empathize** → Understand senior managers’ need for high-level yet actionable dashboards  
2️⃣ **Define** → Focus on profitability, growth, and operational efficiency  
3️⃣ **Ideate** → Map key KPIs (Sales, Profit, Orders, Returns, Margins, AOV, Customer Growth)  
4️⃣ **Prototype & Review** → Build iterative dashboards with 3 lenses: **Overview, Market, Product**  

---

## 📊 Key Insights & Visualizations  

### I. Overview Dashboard  
<img width="1431" height="801" alt="image" src="https://github.com/user-attachments/assets/58273259-e5fd-4cb3-95ff-49e491f7b0ca" /> 

📌 **Findings:**  
1. **Revenue & Profit Surge** – Sales hit **$12.64M (+51.5% YoY)** and profit **$1.47M (+52.3%)**, but profit margin stayed flat at **11.6%**, signaling rising costs.  
2. **Customer Base Growth** – Expanded from 1,309 (2011) → 1,511 (2014), with consistent retention.  
3. **Return Rate Down** – Returns fell by **-49% YoY**, improving operational efficiency.  
4. **Consumer Segment Leads** – Contributed **$6.5M sales**, stable margin (~11–12%).  
5. **Technology Dominates** – Highest revenue ($4.7M) and strong margins (14%), but some SKUs show high returns.  

---

### II. Market Dashboard  
<img width="1433" height="800" alt="image" src="https://github.com/user-attachments/assets/c2d185ab-97bc-419d-8ac2-e51b2f66b8e9" />

📌 **Findings:**  
1. **Market Leaders** – APAC ($3.59M), EU ($2.94M), and US ($2.3M) dominate sales.  
2. **Profitability** – Canada has highest margin (26.6%) despite low revenue, while LATAM & EMEA struggle with <10% margins.  
3. **Growth Markets** – EMEA (+47.4%) and EU (+36.8%) saw strongest sales growth in 2014.  
4. **Customer Distribution** – Central & South regions hold the largest customer base; Africa & Oceania attract most new customers.  
5. **Shipping Efficiency** – Canada & EU face longer ship deltas (~4 days), while APAC balances efficiency with lower return rates.  

---

### III. Product Dashboard  
<img width="1432" height="800" alt="image" src="https://github.com/user-attachments/assets/7ddd0f59-238b-4d14-a99a-700f2a03cc5c" />  

📌 **Findings:**  
1. **Sub-Category Leaders** – Phones, Copiers, and Chairs drive most revenue; Accessories, Art, and Labels yield highest margins.  
2. **Weak Products** – Tables (-8.4% margin) and Furnishings dilute profitability.  
3. **Pareto Analysis** – Top 20% of products contribute ~80% of sales.  
4. **Shipping Insights** – Standard Class dominates sales ($7.6M), showing customers prefer cost-effective delivery.  
5. **Top Products** – Cisco & Motorola Phones, Canon Copiers are most profitable; some Samsung SKUs underperform with negative margins.  

---

## 🔎 Final Conclusion & Recommendation  

### 📌 1. Market Expansion  
- **Insight:** Canada shows the **highest profit margin (26.6%)** despite lower sales; EMEA & Africa demonstrate the **fastest growth rates**.  
- **Recommendation:**  
  - Position **Canada as a strategic profit market**, focus on scaling revenue.  
  - Invest in **EMEA & Africa** to capture long-term growth opportunities.  
  - Closely monitor **operational costs in EU & US** as margins are stagnating.  

---

### 📌 2. Product Portfolio  
- **Insight:** Technology leads with **$4.7M in sales**; Accessories & Labels, while smaller, deliver **higher profit margins**. Conversely, Tables (-8.4% margin) & Furnishings dilute profitability.  
- **Recommendation:**  
  - **Double down on Technology** and high-margin niche products (Accessories, Labels).  
  - Develop new SKUs in **profitable categories**.  
  - **Phase out or reduce focus** on underperforming categories (Tables, Furnishings).  

---

### 📌 3. Customer Growth & Retention  
- **Insight:** 99% of sales come from **existing customers**; Oceania & Africa show **strong new customer acquisition**.  
- **Recommendation:**  
  - Strengthen **customer retention** via loyalty programs, personalized offers, and after-sales services.  
  - Expand **customer acquisition campaigns** in Oceania & Africa with localized marketing.  
  - Apply **Customer Lifetime Value (CLV) segmentation** to guide retention and growth strategies.  

---

### 📌 4. Operations & Efficiency  
- **Insight:** Standard Class dominates ($7.6M sales), indicating customer preference for economical shipping. Canada & EU face **longer ship times (~4 days)**; profit margins in US/EU are stagnating.  
- **Recommendation:**  
  - **Rebalance shipping mix**, optimizing between Standard and faster methods.  
  - Shorten **ship delta in Canada & EU** to improve customer experience.  
  - Replicate the **high-performance model in Central region** across other geographies.  

---

### ✨ Overall Business Impact  
Implementing these recommendations will enable:  
- **Sustainable revenue and profit growth** through market expansion and product optimization.  
- **Higher customer lifetime value & reduced churn** via stronger retention strategies.  
- **Improved operational efficiency** through logistics and shipping optimization.  


