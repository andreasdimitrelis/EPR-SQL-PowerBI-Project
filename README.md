# ERP Sales & Inventory Analysis Project

## 📌 Project Overview
This project simulates a small ERP system focusing on Sales, Customers, Products and Inventory management. 

The goal of the project was to design a relational SQL database and build a reporting layer using Power BI to analyze business performance and key KPIs.

The project demonstrates database design, relationships, SQL querying, and business reporting.

---

## 🛠 Technologies Used
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Power BI Desktop
- DAX (Data Analysis Expressions)

---

## 🗄 Database Structure

The database includes the following main tables:

- Customers
- Orders
- Order_Details
- Products
- Inventory

### Relationships:
- Customers → Orders (1-to-Many)
- Orders → Order_Details (1-to-Many)
- Products → Order_Details (1-to-Many)
- Products → Inventory (1-to-1)

Primary and Foreign Keys were implemented to ensure referential integrity.

---

## 📊 Business KPIs Implemented

The following KPIs were calculated:

- Total Revenue
- Total Profit
- Total Orders
- Low Stock Products
- Revenue by Category
- Top 5 Products by Revenue

Views were created in SQL to support reporting.

---

## 📈 Power BI Dashboard

The reporting layer includes:

- KPI Cards (Revenue, Profit, Orders)
- Bar Chart (Revenue by Category)
- Top N filtering
- Product Performance Table
- Inventory Monitoring (Low Stock)

The dashboard is connected directly to the SQL database.

---

## 🎯 Business Scenario

This project simulates how an ERP system can support:

- Sales performance analysis
- Inventory monitoring
- Product profitability tracking
- Customer order behavior analysis

---

## 📂 Project Files

/SQL  
- ERP_Project_Database.sql (Schema + Data)

/PowerBI  
- ERP_Dashboard.pbix

---

## 🚀 Purpose

This project was developed as part of my preparation for an ERP Consultant / Business Intelligence role, demonstrating practical skills in:

- Database modeling
- SQL querying
- Data relationships
- B
Business KPI reporting
- Power BI dashboard development

---

## 📎 Author
Andreas Dimitrelis
