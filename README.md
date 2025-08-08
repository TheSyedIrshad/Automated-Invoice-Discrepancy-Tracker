# 📊 Automated Invoice Discrepancy Resolution Dashboard  
_**By Syed Irshad Ahmed | Target Role: Business Analyst – Billing & Invoicing | FIS Global (Hypothetical)**_

---

## 🏢 Company Scenario (FIS Global)

**FIS Global** is a leading financial tech provider offering enterprise-grade services like cloud hosting, support, and consulting to B2B clients.  

Each month, clients are billed across multiple service line items — AMC, Hosting, Licensing, Support, etc. However, due to:

- Complex contracts  
- Manual invoice generation  
- Delayed updates to pricing  

**billing discrepancies** creep in — leading to **revenue leakage** and **client dissatisfaction**.

---

## 🔗 Problem Statement

In the recurring billing cycles of large B2B service companies:  

Discrepancies arise due to:

- Misconfigured systems  
- Manual data entry errors  
- Unrecorded service changes  
- Delayed contract updates  

These issues result in:

- Lost revenue  
- Audit overhead  
- Declining trust  

---

## 🎯 Project Objective

Build an **automated dashboard** to:

- ✅ Identify invoice discrepancies across clients and service lines  
- 📉 Quantify revenue loss  
- 📌 Highlight underbilled/overbilled clients  
- 🧠 Support proactive correction & business decisions  

---

## ⚙️ Tools & Tech Stack

- **Excel** – Power Query, PivotTables, Calculated Columns  
- **Tableau** – Interactive visual dashboard  
- **GitHub** – Version control & documentation  

---

## 📁 Dataset Overview

- **Clients**: 120 (C001 – C0120)  
- **Time Period**: 4 months of invoice data  
- **Fields**:
  - `Client_ID`  
  - `Invoice_Month`  
  - `Service_Type` (AMC, Hosting, etc.)  
  - `Agreed_Amount`  
  - `Invoiced_Amount`  
  - `Discrepancy_Amount` (Derived)  
  - `Discrepancy_Type`:  
    - *Overbilled*  
    - *Underbilled*  
    - *Missing*  
    - *Accurate*  

---

## 🧠 Solution Workflow

### ✅ Step 1: Data Consolidation  
- Used Power Query to merge monthly invoice sheets  
- Created calculated columns to detect discrepancy & loss  

### ✅ Step 2: Discrepancy Logic  
Used IF conditions to define:

- **Overbilled**: Invoiced > Agreed  
- **Underbilled**: Invoiced < Agreed  
- **Missing**: No invoice raised  
- **Accurate**: Exact match  

### ✅ Step 3: Dashboard Design  
Built interactive dashboards in Excel and Tableau with:

- 📊 KPI Cards:
  - Total Discrepancies  
  - Total ₹ Loss  
  - Avg. % Discrepancy  
  - # Affected Clients  

- 📈 Charts:
  - Discrepancy Type vs. Loss  
  - Monthly Error Trends  
  - Heatmap (Client vs. Service)  
  - Drill-down View: Record-level  

### ✅ Step 4: Insights & Recommendations

- **Consulting** & **AMC** had highest error rates  
- Advised:  
  - Automated invoice validation  
  - Discrepancy alerts  
  - Regular audits  

---

## 📈 Results & Business Impact

- 💸 ₹12,000+ in potential losses flagged  
- 🔍 40+ records isolated for review  
- 🧠 80% improvement in discrepancy visibility  

### Real-World Impact:

- 📉 Reduced manual audit time  
- ⚠️ Early warning for billing errors  
- 📊 Strategic reporting for leadership  

---

## 🧠 Learnings

- Built a **decision-support system**  
- Learned **real-world Excel + Tableau integration**  
- Understood importance of **domain + process knowledge** in analytics  

---

## 🔮 Future Scope

- 🔔 Power Automate: Set up discrepancy alerts  
- ⌛ Include payment delays & credit note tracking  
- 🤖 Build anomaly detection model in Python  

---

## 📌 Links

- [📊 Excel Dashboard (.xlsx)](https://github.com/TheSyedIrshad/Automated-Invoice-Discrepancy-Tracker/blob/main/Excel_Dashboard_Discrepancy_Tracker.xlsx)
- [📈 Tableau Public Dashboard](https://public.tableau.com/app/profile/irshad.ahmed1445/viz/Dashboard_17545892274520/AutomatedDiscrepancyTracker)
  
---

## 🤝 Let’s Connect

📧 thesyedirshad17@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/thesyedirshad/)  
🌐 [Portfolio](https://github.com/TheSyedIrshad)
