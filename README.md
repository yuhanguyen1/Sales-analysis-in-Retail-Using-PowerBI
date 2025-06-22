# Global-Superstore-Sales-Analysis
Used Power BI to visualize sales overview of Global Superstore, create actionable insights and recommendations.

Author: Nguyen Anh Huy

Date: 18/03/2025

Tools used: Power BI (DAX & Visualization)

## Table of Contents

[I. Background & Overview](https://github.com/yuhanguyen/Global-Superstore-Sales-Analysis/blob/main/README.md#i-background--overview)

[II. Dataset Description & Data Structure](https://github.com/yuhanguyen/Global-Superstore-Sales-Analysis/blob/main/README.md#ii-dataset-description--data-structure)

[III. Design Thinking Process](https://github.com/yuhanguyen/Global-Superstore-Sales-Analysis/blob/main/README.md#iii-design-thinking-process)

[IV. Key Insights & Visualizations](https://github.com/yuhanguyen/Global-Superstore-Sales-Analysis/blob/main/README.md#iv-key-insights--visualizations)

[V.  Final Conclusion & Recommendations](https://github.com/yuhanguyen/Global-Superstore-Sales-Analysis/blob/main/README.md#v--final-conclusion--recommendations)

## I. Background & Overview

Objective:

This project uses Power BI DAX & Visualization tool to analyze sales data from Global Superstore to:

✔️ Have a better look at sales trends and performance, create actionable insights for further action.

✔️ Monitorize product portfolio's performnance, identify top product categories & top regions.

👤 Who is this project for?

✔️ Data analysts & business analysts

✔️ Sales manager & stakeholders

## II. Dataset Description & Data Structure

**Orders.csv**

| Column | Data type | Description |
| :---: | :---: | :---: |
| Order ID  | TEXT | ID of the order |
| Order Date | DATETIME | The date the order was placed |
| Ship Date | DATETIME | The date the order was delivered |
| Region | TEXT | Name of the region where the order was placed |
| Product ID | TEXT | ID of the ordered product |
| Category | TEXT | Category of the ordered product |
| Sub-Category | TEXT | Sub-category of the ordered product |
| Product Name | TEXT | Name of the ordered product |
| Sales | FLOAT | The total price of the order |
| Quantity | INTEGER | The number of product ordered |
| Profit | FLOAT | The total profit of the order |

**People.csv**

| Column | Data type | Description |
| :---: | :---: | :---: |
| Person | TEXT | Name of Salesperson |
| Region | TEXT | Region where the Salesperson is in chart of |

**Returns.csv**

| Column | Data type | Description |
| :---: | :---: | :---: |
| Returned | BOOLEAN | Returned orders |
| Order ID | TEXT | ID of returned orders |

**Data Model**

![image](https://github.com/user-attachments/assets/011aa946-092d-4e70-8db9-1396b61d2296)


## III. Design Thinking Process
The Design Thinking Process was implied to understand stakeholders' need to create the best dashboard. The process consist of the following 4 steps:

1️⃣ Empathize

![image](https://github.com/user-attachments/assets/e263602f-9f82-4775-b6a4-7f1cfb5cabf3)

![image](https://github.com/user-attachments/assets/de8335d1-26d7-4998-8532-faf045be4886)

2️⃣ Define point of view

![image](https://github.com/user-attachments/assets/7aa98ed5-206e-4b05-a031-65e5de922f30)

![image](https://github.com/user-attachments/assets/94c632f3-26cc-46b4-b8b4-afea8ff23651)

3️⃣ Ideate

![image](https://github.com/user-attachments/assets/7c3d2b3f-0de6-4f42-8f8d-47c9fffe628c)

4️⃣ Prototype and review

![image](https://github.com/user-attachments/assets/2944cb63-e235-45d5-90bc-43fe8048a906)

## IV. Key Insights & Visualizations

**Dashboard**

![image](https://github.com/user-attachments/assets/efff906f-050f-45f9-afe1-d9d72cb2c04f)

**Key Insights**

**OVerview**

Sales reached $12.64M, with $1.47M profit → Profit margin of about 11.6%.

Total orders: 26K orders, but 3,050 orders were returned, corresponding to a return rate of 4.55%.

Sales trend over time: Sales growth was quite stable from 2011-2014, but there were some fluctuations. The first and second quarters of the years recorded lower sales compared to the third and fourth quarters.


**Region**

Central has the highest sales ($2.8M)

Canada & Caribbean has the lowest sales ($0.1M & $0.3M)

Southeast Asia has great potential ($0.9M) due to its high population and growing economy


**Category**

Technology accounts for the largest share (37.53%)

Furniture also has high sales, but may have low profit margins due to high costs.

Office Supplies has a share of nearly 30%, but low order value.

**Sub-category**

Phones are the best-selling product → But the profit margin is quite low due to high costs

Chairs and Copiers are also very potential, possibly due to high office demand.

Some categories have very low sales, which may need to be eliminated or the strategy adjusted.

Tables are the only item with negative profit (-8.46%)

## V.  Final Conclusion & Recommendations

**Region**

Strengthen marketing strategy in Southeast Asia, as this region has a large population and strong economy.

Optimize costs in Central to increase profits.

Consider exiting or improving strategy in Canada & Caribbean.


**Category**

Expand your portfolio of high-end technology or products with better profit margins.

Boost marketing & upsell for Furniture, especially high-value products.

Run combo promotion campaigns for Office Supplies to increase order value.


**Sub-category**

Expand phone portfolio, add upsell accessories to increase revenue.

Increase advertising for chairs & photocopiers, especially in the business segment.

Eliminate or optimize low-sales or low-profit categories such as Tables , Fasteners, or Envelopes.
