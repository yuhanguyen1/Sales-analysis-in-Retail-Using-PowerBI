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

![image](https://github.com/user-attachments/assets/7d4a7250-8a29-478c-b5fc-e80ab0cfb8c5)

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

**Tổng Quan**

Doanh số đạt $12.64M, với lợi nhuận $1.47M → Tỷ suất lợi nhuận khoảng 11.6%.

Tổng số đơn hàng: 26K đơn, nhưng có 3,050 đơn bị hoàn trả, tương ứng tỷ lệ hoàn trả 4.55%.

Xu hướng doanh số theo thời gian: Doanh số tăng trưởng khá ổn định từ 2011-2014, nhưng có một số biến động. Quý I và II của các năm ghi nhận doanh số thấp hơn so với quý III và IV.


**Doanh số theo khu vực**

Central có doanh số cao nhất ($2.8M)

Canada & Caribbean có doanh số thấp nhất ($0.1M & $0.3M)

Southeast Asia (Đông Nam Á) có tiềm năng lớn ($0.9M) vì có dân số cao và nền kinh tế đang phát triển mạnh


**Danh mục sản phẩm**

Công nghệ (Technology) chiếm tỷ trọng lớn nhất (37.53%)

Nội thất (Furniture) cũng có doanh số cao, nhưng có thể có biên lợi nhuận thấp do chi phí cao.

Văn phòng phẩm (Office Supplies) có tỷ trọng gần 30%, nhưng giá trị đơn hàng thấp.


**Sub-category**

Điện thoại (Phones) là sản phẩm bán chạy nhất → Nhưng biên lợi nhuận khá thấp do chi phí cao

Ghế (Chairs) và Máy photocopy (Copiers) cũng rất tiềm năng, có thể do nhu cầu văn phòng cao.

Một số danh mục có doanh số rất thấp, có thể cần loại bỏ hoặc điều chỉnh chiến lược.

Bàn (Tables) là mặt hàng duy nhất có lợi nhuận âm (-8.46%)

## V.  Final Conclusion & Recommendations

**Khu vực**

Đẩy mạnh chiến lược tiếp thị tại Southeast Asia, vì khu vực này có dân số lớn và nền kinh tế phát triển mạnh.

Tối ưu hóa chi phí tại Central để tăng lợi nhuận.

Xem xét việc rút khỏi hoặc cải tiến chiến lược tại Canada & Caribbean.


**Danh mục sản phẩm**

Mở rộng danh mục công nghệ cao cấp hoặc sản phẩm có biên lợi nhuận tốt hơn.

Đẩy mạnh marketing & upsell cho Furniture, đặc biệt là các sản phẩm có giá trị cao.

Chạy chiến dịch khuyến mãi combo cho Office Supplies để tăng giá trị đơn hàng.


**Sub-category**

Mở rộng danh mục điện thoại, bổ sung thêm phụ kiện upsell để tăng doanh thu.

Tăng quảng cáo cho sản phẩm ghế & máy photocopy, đặc biệt trong phân khúc doanh nghiệp.

Loại bỏ hoặc tối ưu danh mục có doanh số hoặc lợi nhuận thấp như Tables Labels, Fasteners, hoặc Envelopes.
