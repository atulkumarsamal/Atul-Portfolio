# P2P & Inventory Management System

## 📌 Overview

The **P2P & Inventory Management System** is an Excel-based management application designed to organize and automate key Purchase-to-Pay (P2P), inventory, supplier, and management activities.

The project is being developed using **Microsoft Excel, Excel Tables, formulas, and VBA automation**.

The main objective is to create an easy-to-use interface where users can enter, manage, update, and analyze business data without directly working with raw data tables.

---

## 🎯 Project Objectives

- Simplify Purchase-to-Pay data management
- Maintain centralized purchase and inventory records
- Reduce manual data entry
- Automate repetitive Excel tasks using VBA
- Provide a simple dashboard for management reporting
- Maintain supplier information
- Track inventory-related transactions
- Create a structured and user-friendly Excel application

---

## 🖥️ System Structure

The system is divided into different functional areas:

### 1. Dashboard

The Dashboard provides a central overview of the system.

Planned information includes:

- Purchase summary
- Inventory summary
- Supplier information
- Pending transactions
- Key performance indicators
- Charts and visual reports

---

### 2. Manager

The Manager section is intended for management-level activities and reporting.

Possible functions:

- Management overview
- Performance monitoring
- Purchase analysis
- Inventory analysis
- Supplier analysis
- Reports

---

### 3. Purchase Department

The Purchase Department manages the purchasing process.

Planned modules:

- Purchase Requisition
- Purchase Quotation
- Purchase Order
- Purchase Invoice
- Purchase Return

Basic process:

Purchase Requisition
        ↓
Purchase Quotation
        ↓
Purchase Order
        ↓
Purchase Invoice
        ↓
Payment / Completion

---

### 4. Store Department

The Store Department manages inventory-related activities.

Planned modules:

- Initial Rejection
- Loss During Transit
- Goods Receipt Note (GRN)
- Subsequent Rejection
- Shortage
- Material Issue

Basic inventory flow:

Purchase Order
        ↓
Goods Received
        ↓
GRN
        ↓
Inventory
        ↓
Material Issue

---

### 5. Supplier Master

The Supplier section is used to maintain supplier-related information.

Planned functions:

- Add New Supplier
- Available Suppliers
- Supplier Master Data
- Pending Supplier Activities
- Supplier Search

Supplier information may include:

- Supplier ID
- Supplier Name
- Contact Details
- Address
- GSTIN
- PAN
- Payment Terms
- Supplier Status

---

## ⚙️ Technology Used

- Microsoft Excel
- Excel Tables
- Excel Formulas
- VBA (Visual Basic for Applications)
- Pivot Tables
- Charts
- Data Validation
- Conditional Formatting

---

## 🔄 Data Entry Automation

The system will use VBA to automate data entry.

Example:

User enters information into an Excel form:

    Supplier
    Product
    Quantity
    Rate
    Date

            ↓

        SUBMIT

            ↓

       VBA Macro

            ↓

      Excel Data Table

The VBA macro can automatically:

- Validate input
- Create a new record
- Generate an ID
- Calculate amounts
- Save the record
- Clear the entry form
- Display confirmation messages

---

## 🗄️ Data Management

Raw transaction data will be maintained separately from the user interface.

Example:

### Entry Form

    Supplier:  ABC Ltd
    Product:   Laptop
    Quantity:  10
    Rate:      ₹50,000

            ↓

### Data Table

| ID | Date | Supplier | Product | Quantity | Rate | Amount |
|----|------|----------|---------|----------|------|--------|
| 1 | 17-09-2026 | ABC Ltd | Laptop | 10 | 50,000 | 5,00,000 |

This separation helps keep the user interface clean while maintaining structured data in the background.

---

## 🚀 Planned Features

The project is currently under development.

Future features include:

- [ ] Purchase Requisition
- [ ] Purchase Quotation
- [ ] Purchase Order
- [ ] Purchase Invoice
- [ ] Purchase Return
- [ ] GRN
- [ ] Inventory Tracking
- [ ] Stock Issue
- [ ] Supplier Master
- [ ] Search Function
- [ ] Edit / Update Records
- [ ] Delete Records
- [ ] VBA-based Data Entry Forms
- [ ] Automated Calculations
- [ ] Dashboard
- [ ] Management Reports
- [ ] Data Validation
- [ ] Error Handling

---

## 📁 Workbook Structure

Current workbook structure:

    P2P & Inventory Management System
    │
    ├── Dashboard
    ├── Manager
    ├── Purchase_dept
    ├── Store_dept
    └── Supplier_master

Additional database/data sheets and VBA modules will be added as development progresses.

---

## 📚 Learning Objective

This project is also being developed as a practical learning project to understand:

- Excel automation
- VBA programming
- Business process automation
- Purchase-to-Pay processes
- Inventory management
- Supplier management
- Financial data management
- Management reporting

---

## ⚠️ Project Status

**Status: Work in Progress 🚧**

The system is currently under development. Features and modules will be added progressively.

This project is intended for **learning, demonstration, and portfolio purposes**.

---

## 👨‍💻 Author

**Atul Kumar Samal**

Cost & Management Accounting

### Skills Demonstrated

- Microsoft Excel
- Excel VBA
- Financial & Management Accounting
- P2P Process Understanding
- Inventory Management
- Data Analysis
- Dashboard Development
- Business Process Automation
