# 📊 Olist Retail Insights Dashboard — Power BI

An interactive **Power BI dashboard** developed as part of the **Elevvo Data Analyst Internship**.

This project was completed as my **third task**, where I chose Task 8 as a challenge to step outside my comfort zone and gain hands-on experience with Power BI, DAX, data modeling, and interactive dashboard development.

---

## 📌 Project Overview

The dashboard analyzes the **Brazilian E-Commerce Public Dataset by Olist**, transforming raw e-commerce data into meaningful visual insights.

The main goal is to provide an interactive overview of sales performance, customer activity, orders, products, and payment methods.

---

## 📂 Dataset

**Brazilian E-Commerce Public Dataset by Olist**

The dataset contains Brazilian e-commerce data covering orders, customers, products, sellers, payments, reviews, and other related information.

🔗 **Kaggle Dataset:**
[https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce]

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**

---

## 🔄 Data Preparation

The dataset was prepared before building the dashboard, including:

* Reviewing the imported tables
* Checking and correcting data types
* Preparing date and numerical columns
* Creating relationships between related tables
* Organizing the data model for analysis

---

## 🧩 Data Modeling

The project uses multiple related tables from the Olist dataset, including:

* Customers
* Orders
* Order Items
* Products
* Sellers
* Payments
* Reviews
* Product Category Translation

Relationships between the tables were used to allow interactive filtering and analysis across the dashboard.

---

## 📐 DAX Measures

Several DAX measures were created to calculate the main KPIs:

```DAX
Total Revenue =
SUM('olist_order_items_dataset'[price])
```

```DAX
Total Orders =
DISTINCTCOUNT('olist_orders_dataset'[order_id])
```

```DAX
Total Customers =
DISTINCTCOUNT('olist_customers_dataset'[customer_unique_id])
```

```DAX
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

---

## 📈 Dashboard KPIs

The dashboard provides an overview of:

* 💰 Total Revenue
* 🛒 Total Orders
* 👥 Total Customers
* 📦 Average Order Value

---

## 📊 Visualizations

The dashboard includes:

* **Revenue Over Time**
* **Revenue by Product Category**
* **Orders by State**
* **Top 10 Products**
* **Payment Method Distribution**

These visualizations provide different perspectives on the e-commerce performance and allow users to explore the data interactively.

---

## 🎛️ Interactive Features

The dashboard includes slicers and filters that allow users to dynamically analyze the data by:

* **State**
* **Product Category**
* **Date**

Users can select different values and explore how the dashboard insights change based on their selections.

---

## 🖼️ Dashboard Preview

![Olist Retail Dashboard](dashboard.png)

---

## 🎯 Key Learning Outcomes

This project provided hands-on experience in:

* Building interactive dashboards with Power BI
* Creating DAX measures
* Working with multiple related tables
* Understanding data modeling and relationships
* Designing business-focused visualizations
* Using slicers and filters for interactive analysis
* Transforming raw data into a structured BI dashboard

---

## 👩‍💻 Internship

This project was completed as part of the **Elevvo Data Analyst Internship**.


