## Flipkart-Sales-Analysis-Dashboard
Flipkart Sales Analysis Dashboard using Power BI — includes data cleaning, data modeling, KPI creation, and full interactive visualizations for product, customer, and sales performance insights.

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tool](https://img.shields.io/badge/Tools-Excel%20%7C%20Power%20BI-blue)
![Data](https://img.shields.io/badge/Data-Flipkart%20E--Commerce-orange)
![Author](https://img.shields.io/badge/Author-Ummu%20Abeeba-purple)

---

## 🛍️ **Project Overview**

This project presents an interactive **Flipkart Sales Analysis Dashboard** built using **Power BI**, with initial data verification and preparation using **Excel**.

The goal of this project is to analyze Flipkart’s sales performance and understand:

* Product performance
* Customer purchase behavior
* Revenue & order trends
* Return and cancellation patterns
* Delivery efficiency

The dashboard enables quick, actionable insights for key business decisions.

---

## 📂 **Dataset Overview**

This analysis uses two datasets:

### 📄 `Orders.csv`

Contains:

* Order ID
* Order date
* Delivery date
* Payment method
* Delivery status
* Quantity
* Total amount
* Customer location

### 📄 `Details.csv`

Contains:

* Product ID
* Category
* Sub-category
* Seller information
* Product attributes

---

## 🧰 **Tools & Technologies**

| Category          | Tools Used      |
| ----------------- | --------------- |
| **Data Cleaning** | Microsoft Excel |
| **Data Modeling** | Power BI        |
| **Visualization** | Power BI        |
| **File Formats**  | `.csv`, `.pbix` |

---

## 🚀 **Project Workflow**

### **1️⃣ Data Cleaning (Excel)**

* Removed duplicates
* Standardized column formats
* Cleaned date fields
* Validated numeric and categorical values

---

### **2️⃣ Data Modeling (Power BI)**

* Built relationships between Orders and Details tables
* Created essential **DAX measures** including:

  * Total Sales
  * Total Quantity
  * Average Order Value
  * Return Rate
  * Delivery Success %
* Designed a star-schema style model for performance

---

### **3️⃣ Dashboard Development**

📊 File included: **`Flipkart sales report dashboard.pbix`**

Dashboard includes:

* **Sales Overview (KPIs)**
* **Revenue by Category & Subcategory**
* **Customer Location Insights**
* **Top-Selling Products**
* **Order Trends (Daily, Monthly)**
* **Returns & Cancellations Analysis**
* **Payment Method Distribution**

---

## 📸 **Dashboard Preview**

*(Add screenshots after uploading images to /screenshots folder)*

```md
![Dashboard Screenshot 1](screenshots/dashboard.png)
```

---

## 💡 **Key Insights**

✔ Top-selling categories drive majority of revenue
✔ Certain regions contribute significantly higher sales
✔ UPI & COD are most preferred payment methods
✔ A few product categories have high return rates
✔ Monthly revenue shows clear seasonal trends

---

## 📦 **Project Files**

| File                                   | Description              |
| -------------------------------------- | ------------------------ |
| `Orders.csv`                           | Raw order-level dataset  |
| `Details.csv`                          | Product/category dataset |
| `Flipkart sales report dashboard.pbix` | Power BI dashboard       |
| `README.md`                            | Documentation            |

---


## 🔧 **How to Use This Project**

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/Flipkart-Sales-Analysis.git
   ```

2. Open the CSV files for data review.

3. Launch **Power BI Desktop** and open:

   ```
   Flipkart sales report dashboard.pbix
   ```

4. Refresh data if needed.

---

## 👩‍💻 **Author**

**Ummu Abeeba**
📧 **[abeeba3356@gmail.com](mailto:abeeba3356@gmail.com)**
💼 *Aspiring Data Analyst | Excel | Power BI | Dashboard Design*

---

## ⭐ **If you found this project useful, please give it a star on GitHub!**
