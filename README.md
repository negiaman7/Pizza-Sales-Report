# Pizza-Sales-Report
I created an interactive Pizza Sales report to analyze a full year of business performance (Jan–Dec 2015). This repository contains an end–to–end **Pizza Sales Analytics** project built in **SQL** and **Power BI**.  The dashboard provides KPI tracking, seasonal demand insights, customer buying patterns, and best/worst-performing products to support strategic decision-making. The dashboard analyzes a full year of pizza shop performance (Jan–Dec 2015) and surfaces insights around revenue, order behaviour, product performance and customer preferences.

---

## 🧩 Business Problem

A pizza store wants to understand:
- When are the **busiest days and times**?
- Which **pizza categories and sizes** generate the most revenue?
- What are the **best and worst performing pizzas** by revenue, quantity and orders?
- How do sales behave **month to month** across the year?

## 📊 Key Metrics (KPIs)

From the dashboard, for the period **01-01-2015 to 31-12-2015**:

- **Total Revenue:** `818K`
- **Total Orders:** `21.35K`
- **Total Pizzas Sold:** `49,574`
- **Average Order Value (AOV):** `38.31`
- **Average Pizzas per Order:** `2.32`

---

## 🔍 Main Insights

### 1. Busiest Days & Times
- Orders are **highest on weekends**, especially **Friday and Saturday evenings**.
- This suggests focusing staffing, delivery capacity and offers around weekend peaks.

### 2. Monthly Performance
- **July** and **January** show the **maximum orders** across the year.
- There is a visible dip in **September–October**, indicating potential scope for seasonal or targeted campaigns in those months.

### 3. Category Performance
- **Classic** pizzas contribute the **highest share of sales and orders**.
- Other categories (**Supreme, Chicken, Veggie**) share the remaining volume, each contributing a significant but smaller portion.

### 4. Size Performance
- **Large size pizzas** dominate with the **maximum revenue contribution (~46%)**.
- **Medium** and **Regular** sizes follow; **X-Large** and **XX-Large** represent a very small share.

### 5. Best Sellers (Top Performing Pizzas)
- **Thai Chicken Pizza** – contributes the **maximum revenue**.
- **Classic Deluxe Pizza** – contributes the **maximum total quantity sold** *and* **maximum total orders**.
- These are strong candidates for featured items, combos or upsell campaigns.

### 6. Worst Sellers (Bottom Performing Pizzas)
- **Brie Carre Pizza** – contributes the **minimum revenue, quantity and total orders**.
- This pizza may need recipe changes, marketing support or removal from the menu.

---

## 🧮 About the Dataset

- Time period: **Jan 2015 – Dec 2015**
- Grain: **Order and pizza-level transactions**
- Typical fields used:
  - Order Date & Time
  - Pizza Name, Category and Size
  - Quantity
  - Unit Price and Total Price
---

## 🛠 Tech Stack & Power BI Features

- **Power BI Desktop**
  - Data import and cleaning
  - Data modelling with relationships
  - Calculated columns & measures (DAX)
  - Interactive visuals, slicers and filters
- **DAX Measures (examples):**
  - Total Revenue
  - Total Orders
  - Total Pizzas Sold
  - Average Order Value
  - Average Pizzas per Order

- **Visualization Types:**
  - KPI cards
  - Column charts (Daily trend, orders by month)
  - Donut charts (Sales by category, sales by size)
  - Bar charts (Top/Bottom pizzas by revenue, quantity, orders)

Screenshot
<img width="981" height="541" alt="Page 1" src="https://github.com/user-attachments/assets/4e543d7b-ae70-4284-bb57-6bc171d4ab8c" />
<img width="983" height="543" alt="Page 2" src="https://github.com/user-attachments/assets/eb69867b-ab86-4dd8-8959-c138646f5aff" />

