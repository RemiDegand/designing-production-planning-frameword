# 🏭 Production Planning Tool & Commercial Performance Monitoring

## 🎯 Objective
Design and deploy a **reliable production planning tool** and **commercial performance monitoring dashboards**
to support operational and managerial decision-making within a Business Unit.

This project was carried out during an internship within the **PDV Business Unit of Oslo**, a company providing
payment and point-of-sale solutions to professional clients.

---

## 🏢 Business Context
- Business Unit revenue: ~€4M annually  
- Several hundred professional clients  
- Production planning and performance tracking initially handled through an unstructured Excel file  

The existing production planning file was:
- Poorly structured (multiple tables by order status in a single worksheet)
- Open to uncontrolled modifications
- Not suitable for reliable data analysis or performance monitoring  

As a result, **no reliable operational or commercial KPIs** were available to effectively pilot the activity.

---

## ❗ Problem Statement
- Lack of data reliability due to uncontrolled manual inputs
- No standardized production planning structure
- Impossible to perform consistent statistical or performance analysis
- No clear visibility on production status, sales performance, or activity trends

---

## 🛠 Tools Used
- **Excel (advanced)** – structured production planning, data validation, access control  
- **MyReport** – data extraction and modeling  
- **ERP accounting & operational data**

---

## ⚙️ Solution Implemented

### 1️⃣ Redesign of the Production Planning Tool (Excel)
A new Excel-based production planning tool was designed around a **single centralized data table**, including:

- Standardized data entry using:
  - Dropdown lists
  - Enforced formats per column
- Addition of an **order status field**
- Conditional formatting to:
  - Monitor activity
  - Detect anomalies
- Access rights management:
  - Cell locking
  - Editing rights restricted by role
  - Each user could only modify their own columns

This ensured **data consistency, traceability, and reliability**.

---

### 2️⃣ Commercial Performance Monitoring Dashboards
Production data was extracted via **MyReport** and structured through a dedicated data model to build
decision-support dashboards.

#### KPIs monitored:
- Revenue  
- Margin  
- Number of orders  
- New Business  
- Target vs actual performance  

#### Analysis dimensions:
- Sales representative  
- Product  
- Production manager  
- Order status  

---

### 3️⃣ Dashboard Structure

#### 📊 Global Commercial Performance Dashboard
Provides a consolidated view of the Business Unit’s activity:
- Current month production overview  
- Sales representatives’ performance  
- Year-to-date statistics  
- Customer base overview  
![Prod Global Current Month](https://github.com/user-attachments/assets/c2e2eb2d-a831-4783-be8c-686faee058f2)


#### 👤 Individual Sales Dashboards
Personalized dashboards restricted to each sales representative:
- Monthly or selected period performance  
- Year-to-date statistics  
- Personal customer portfolio  
![Prod Sales Team 4](https://github.com/user-attachments/assets/1dd786bd-7d26-4026-b592-0bb3fe4031bd)


---

## 📈 Business Impact
- Significant improvement in **production data reliability**
- Standardized and secured production planning process
- Clear and actionable visibility on commercial performance
- Enabled **data-driven monitoring and decision-making** at both managerial and operational levels

---

## 🔒 Data Confidentiality
All data presented in this repository is **anonymized or simulated** for confidentiality reasons.
