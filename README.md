## 🚲 Bike Sales Data Analysis

This repository contains an end-to-end **data analytics project analyzing bike sales performance**, built to demonstrate skills in **SQL data modeling, data transformation, and Tableau dashboard development**.

The project explores customer purchasing behaviour, product performance, and regional sales trends using the **BikeStores dataset**.

---

## 🔗 Live Dashboard

👉 [View the Bike Sales Dashboard on Tableau Public](https://public.tableau.com/app/profile/justice.sosu/viz/BikeSales_17498547885450/BikeSalesDashboard)

---

## 📊 Dashboard Preview

![Bike Sales Dashboard](images/dashboard.png)

---

## 📊 Project Overview

The goal of this project was to analyze bike sales data to uncover insights into:

- Customer purchasing behaviour
- Product category performance
- Regional and store-level sales trends
- Sales growth over time

The analysis demonstrates the full workflow of a data analyst project:

**Raw Data → SQL Data Modeling → Data Cleaning → Dataset Creation → Tableau Dashboard**

---

## ❓ Business Questions

This analysis aimed to answer several key questions:

- Which **bike categories and brands generate the most revenue?**
- Which **stores and locations perform the best?**
- Who are the **top customers and sales representatives?**
- How have **sales trends changed over time?**
- Are there **seasonal patterns in bike sales?**

---

## 🧠 Approach

### 1️⃣ Data Preparation & Cleaning (MySQL)

Because the original database wasn't available, the dataset was reconstructed manually.

Steps included:

- Creating all tables using `CREATE TABLE`
- Loading data using `INSERT INTO`
- Designing a **normalized relational structure**
- Validating **foreign key relationships**
- Cleaning inconsistent values and formatting dates

The database structure included tables such as:

- customers  
- orders  
- order_items  
- products  
- brands  
- categories  
- stores  
- staffs  

---
### 2️⃣ SQL Data Transformation

Multiple tables were combined using **INNER JOIN queries** to produce a single analytical dataset.

The result was exported as: **BikeStores.csv**
This file combines:

- Customer information
- Product and brand data
- Store locations
- Order details
- Sales values

The dataset was then used as the data source for the Tableau dashboard.

---

#### 3. 📊 Dashboard Creation (Tableau)

The cleaned dataset was imported into **Tableau Public** where an interactive dashboard was built.

Key visualizations include:

- **Sales by Category and Brand**
- **Sales by Store Location**
- **Customer Purchase Analysis**
- **Sales Representative Performance**
- **Monthly and Yearly Sales Trends**

Interactive filters allow users to explore performance across:

- Product categories
- Regions
- Time periods

---

## 📈 Key Insights

Some key insights discovered during the analysis include:

- **Certain bike categories significantly outperform others**, indicating clear product preferences among customers.
- **Sales are concentrated in specific stores and states**, suggesting strong regional demand differences.
- **A small group of customers contribute a large share of total revenue**, highlighting the importance of high-value customers.
- **Sales trends show clear fluctuations across months**, suggesting seasonal demand for bikes.
- **Some sales representatives consistently outperform others**, which may reflect experience or store location advantages.

---
### 🗂️ Repository Structure

```
.
├── BikeStores.sql        # SQL script to join all tables
├── BikeStores.csv        # Final cleaned, joined dataset used for Tableau
├── BikeStores sample databases # Drop existing tables
├── BikeStores sample databases #Create Schema and tables
├── BikeStores sample databases #Insert into tables
├── README.md             # Project documentation

```

---

### 🛠️ Technologies Used

* **MySQL** – Data modeling, cleaning, joining
* **Tableau Public** – Dashboard creation
* **Excel** – Data inspection and CSV formatting

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel">
</p>

---

### 📅 How to Use

1. Clone this repository.
2. Create tables and schema using the sample databases file
3. Run the `BikeStores.sql` file in a local SQL environment to rebuild the database.
4. Use the `BikeStores.csv` file for direct dashboarding or analysis in Excel or Tableau.

---

### ✅ Key Takeaways

* Practiced **manual data modeling** when a source database wasn’t available.
* Strengthened **SQL skills** for data cleaning and joining.
* Learned how to prepare datasets for BI tools like Tableau.
* Focused on **building user-friendly, insightful dashboards** for non-technical audiences.

### License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.  

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>
