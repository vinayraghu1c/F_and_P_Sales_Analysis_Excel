# FNP Sales Analysis Dashboard (Excel + Power Query)

This project is a complete sales data analysis and interactive dashboard built using **Excel 2013** with **Power Query**, Pivot Tables, and Pivot Charts.  
It visualizes order patterns, delivery efficiency, top-performing products, and customer behavior for a fictional flower & gifting brand — **FNP (Ferns N Petals)**.

---

### Project Overview

This project walks through a **complete data analysis lifecycle**:
- Cleaning and preparing raw data
- Extracting useful time-based insights
- Calculating custom metrics like revenue and delivery time
- Creating a dynamic and insightful dashboard with slicers

> Built 100% in Excel (no external BI tools), this dashboard is designed to be fast, lightweight, and interactive.

---

### Dataset Description

The dataset is divided into 3 relational tables:

#### 🧾 `Customers`
| Column | Description |
|--------|-------------|
| `Customer_ID` | Unique ID of each customer |
| `Name` | Full name |
| `City` | Location |
| `Contact_Number`, `Email` | Contact info |
| `Gender`, `Address` | Demographic info |

####  `Products`
| Column | Description |
|--------|-------------|
| `Product_ID` | Unique product code |
| `Product_Name` | Name of product |
| `Category` | Product category (e.g., Flowers, Cakes) |
| `Price (INR)` | Unit price |
| `Occasion` | Associated occasion type |

####  `Orders`
| Column | Description |
|--------|-------------|
| `Order_ID`, `Customer_ID`, `Product_ID` | Join keys |
| `Quantity` | No. of units ordered |
| `Order_Date`, `Order_Time` | Order timestamps |
| `Delivery_Date`, `Delivery_Time` | Delivery timestamps |
| `Location`, `Occasion` | Order-specific location and occasion |

---

###  Data Cleaning & Transformation

In **Power Query**, the following transformations were applied:

- Removed **null values** and obvious **data entry errors**
- Extracted `Order Month`, `Order Day`, `Delivery Month`, and `Delivery Day` from date fields
- Created a new column:  
  **`Revenue = Quantity × Price`**
- Calculated **Delivery Duration (Days)** using date difference
- Unified occasional mapping from two different sources
- Formatted all text and date columns uniformly for cleaner reporting

> All transformations were done using **Power Query**, making the process repeatable and efficient.

---

### Dashboard Features

- Interactive filters using **Slicers** (City, Occasion, Category, etc.)
- KPIs: Total Revenue, Avg Spend per Customer, Avg Delivery Time
- Visuals:
  - Top Products by Revenue
  - Revenue by Occasion and Category
  - Correlation chart between Quantity & Delivery Time
  - Customer distribution by city
- Clean layout optimized for full-screen reporting

---

### 📷 Dashboard Preview
 
👇  
![Dashboard Preview](https://github.com/vinayraghu1c/F_and_P_Sales_Analysis_Excel/blob/main/Dashboard_Preview.png)


---

This project was built from scratch with care — from data wrangling to dashboard styling — as part of my journey to master **data analysis using only Excel**.  
Excel 2013 doesn’t support some modern features, so I handled:
- Custom logic to simulate correlation insights
- Workarounds for slicer behavior and formatting

Let me know if you'd like to collaborate, suggest improvements, or just talk dashboards 😊.

---

### Connect With Me

- Email: vinayraghuwanshi206@gmail.com  
- LinkedIn: https://www.linkedin.com/in/vinay-raghuwanshi

---
# - By Vinay Raghuwanshi

