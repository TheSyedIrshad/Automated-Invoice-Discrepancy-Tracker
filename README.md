📊 Automated Invoice Discrepancy Resolution Dashboard
🏢 Company Context
At FIS Global, a leading financial technology provider offering enterprise-grade subscription services like cloud hosting, consulting hours, support, and licensing to B2B clients, billing accuracy is mission-critical. In such high-scale environments, invoices often contain multiple service line items tailored to each client contract (e.g., AMC, Hosting, Consulting). Due to the volume and variability of agreements, manual discrepancies—such as mismatched amounts, missing entries, or inconsistent frequencies—become frequent. Left unchecked, these small errors can snowball into revenue leakage and client dissatisfaction, ultimately impacting profitability and trust.

________________________________________
🔗 Problem Statement
In the recurring billing process of service-based B2B companies, discrepancies often arise between the agreed contract value and the invoiced amount. These discrepancies may occur due to manual errors, misconfigured billing systems, unrecorded service variations, or delays in updates to pricing agreements. Over time, this leads to revenue leakage, trust deficits with clients, and operational inefficiencies.
The goal is to develop an interactive and automated solution to:
•	Track and categorize invoice discrepancies across service types and clients
•	Quantify potential revenue loss
•	Enable business users to take proactive corrective actions
•	Improve billing accuracy and operational control
________________________________________
⚙️ Tools & Technologies Used
•	Excel (Power Query, Formulas, Pivot Tables, Dashboard Design)
•	Tableau (Dashboarding, Visual Analytics)
•	Power BI (Alternative, optional)
•	GitHub (Version control, documentation)
________________________________________
💡 Business Context & Importance
B2B service companies that offer subscriptions, consulting, support, and software licensing often have multi-line item invoices. With varied service agreements across multiple clients (e.g., AMC, Hosting, Consulting), human error is inevitable. A small mismatch in billing can scale to significant losses across months.
An automated discrepancy tracker empowers:
•	Finance teams to audit invoices
•	Account managers to ensure client satisfaction
•	Leadership to spot high-risk revenue segments
________________________________________
🔄 Dataset Overview
•	Clients: C001 to C0120 (120 clients)
•	Service Types: AMC, Cloud Hosting, Consulting Hours, License Renewal, Support Ticket Closure
•	Fields:
o	Client_ID
o	Invoice_Month
o	Service_Type
o	Agreed_Amount
o	Invoiced_Amount
o	Discrepancy_Amount (derived)
o	Discrepancy_Type (Overbilled / Underbilled / Missing / Accurate)
________________________________________
✅ Solution Approach
Step 1: Data Consolidation
•	Combined multiple monthly invoice sheets using Power Query
•	Created calculated columns for discrepancy and loss detection
Step 2: Discrepancy Logic & Categorization
•	Used IF logic to label discrepancy types:
o	Overbilled: Invoiced > Agreed
o	Underbilled: Invoiced < Agreed
o	Missing: Invoice not raised
o	Accurate: Invoiced = Agreed
Step 3: Dashboard Design (Excel & Tableau)
•	KPI Cards: Total Loss, Total Discrepancies, Avg. % Discrepancy, # of Affected Clients
•	Visuals:
o	Loss by Discrepancy Type
o	Monthly Trends of Errors
o	Heatmap: Clients vs. Service Type
o	Drill-down: Individual Discrepancies
Step 4: Insights & Recommendations
•	Identified high-risk service types (e.g., Consulting and AMC)
•	Pinpointed specific clients contributing to majority of revenue leakage
•	Recommended implementing invoice validation checks & automated billing tools
________________________________________
📈 Key Results
•	₹12+ thousand identified in cumulative loss across 4 months
•	Over 40+ invoice records flagged for manual review
•	Improved discrepancy visibility by 80%
________________________________________
🥇 Business Impact
•	Finance Teams: Reduced manual audit time
•	Revenue Ops: Preventive loss detection before client escalations
•	Management: Real-time reporting for strategic decision-making
________________________________________
📚 Learnings & Takeaways
•	Hands-on experience with Power Query and Tableau data pipeline
•	Learned to build a real-world, decision-support system for recurring business problems
•	Importance of domain understanding in analytics
________________________________________
💻 Future Scope
•	Integrate alert system using Power Automate
•	Expand scope to include payment delays and credit note mismatches
•	Build anomaly detection model using Python for advanced scenarios
________________________________________


👤 Author
Irshad Ahmed
Aspiring Business Analyst | BBA Business Analytics | SaaS Dreamer
[LinkedIn Profile] | [GitHub Repository]

