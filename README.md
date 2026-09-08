# Integrated MIS Reporting & Management Dashboard | Excel

## 📌 Project Overview

An end-to-end Excel-based MIS reporting project developed for a fictional manufacturing company, **ABC Pvt. Ltd.**

The project consolidates operational data from **Sales, Finance, Production, Inventory and Manpower** into departmental MIS reports and an Executive Summary Dashboard.

The objective is to demonstrate how raw business data can be transformed into **validated, structured and management-ready information** using Excel.

---

## 🎯 Business Objective

The project was designed to help management monitor:

- Sales performance and growth
- Production efficiency and achievement
- Inventory position and stock risks
- Budget vs Actual financial performance
- Employee attendance and overtime
- Data-quality exceptions requiring verification

---

## 🔄 MIS Workflow

**Raw Data → Data Cleaning → Data Validation → Reconciliation → Analysis → KPI Reporting → Dashboard → Management Insights**

---

## 📊 Reports Included

### Executive Summary
- Total Sales & MoM Growth
- Production & Achievement %
- Rejection %
- Inventory Value & Low Stock
- Budget vs Actual
- Budget Utilization
- Employee Count
- Attendance & Overtime
- Management Insights

### Sales MIS
- Total Sales
- Quantity Sold
- Average Order Value
- Average Discount
- Monthly Sales Trend
- Sales by Region
- Sales by Product
- Salesperson Performance
- Top Customers

### Finance MIS
- Budget vs Actual
- Budget Utilization
- Monthly Expense Trend
- Expense Category Mix
- Expense by Account
- Monthly Variance

### Production MIS
- Total Production
- Production Achievement %
- Monthly Production Trend
- Production by Production Line
- Production by Shift
- Monthly Downtime Trend
- Rejection by Product

### Inventory MIS
- Inventory Value
- Closing Stock
- Low Stock Materials
- Material Consumption
- Material-wise Inventory Position
- Annual Purchase Volume
- Annual Consumption Volume

### Manpower MIS
- Total Employees
- Attendance %
- Leave %
- Overtime Hours
- Employees by Department
- Attendance by Department
- Overtime by Department
- Attendance by Shift
- Overtime by Shift

---

## 🧹 Data Cleaning & Validation

Before reporting, the datasets were reviewed for common data-quality issues such as:

- Blank values
- Typographical errors
- Negative quantities
- Duplicate/potential duplicate records
- Revenue mismatches
- Budget/Actual inconsistencies
- Inventory reconciliation issues
- Negative overtime
- Invalid or unusual operational values

A separate **Data Quality Log** was maintained to record:

**Issue → Column → Action → Status → Resolution**

Records requiring business verification were flagged and excluded from relevant MIS calculations where necessary.

---

## 🛠️ Excel Skills Demonstrated

- Excel Tables
- Pivot Tables
- Pivot Charts
- KPI Reporting
- Dashboard Development
- Conditional Formatting
- Data Validation
- Data Cleaning
- Data Reconciliation
- `XLOOKUP`
- `UNIQUE`
- `FILTER`
- `MAXIFS`
- `IF`
- `COUNTIF`
- `COUNTBLANK`
- `COUNTA`
- `TEXTJOIN`

---

## 💡 Key Business Insights

The project identified several management-level observations, including:

- December recorded strong sales growth.
- Production achieved approximately 90% of its target.
- Two materials were below reorder levels.
- Actual financial expenditure exceeded the approved budget.
- Production accounted for the highest manpower and overtime utilization.
- Data-quality exceptions were identified and documented for departmental verification.

---

## 📁 Project Structure

```text
Integrated-MIS-Reporting/
│
├── README.md
│
├── Excel/
│   └── ABC_Integrated_MIS.xlsx
│
├── Documentation/
│   └── Integrated_MIS_Project_Documentation.pdf
