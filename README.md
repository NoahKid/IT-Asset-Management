📊 IT Asset Management & Tracking System
Efficient IT Asset Lifecycle Tracking Using Microsoft Excel

📌 Project Overview
This project is a structured IT asset tracking system built using Microsoft Excel. It enables organizations to efficiently manage their hardware and software inventory, track lifecycle stages, and automate warranty monitoring with conditional formatting.

✅ Tracks IT assets from requisition to retirement
✅ Standardizes data entry with validation & drop-down lists
✅ Automates warranty expiration tracking with conditional formatting
✅ Generates reports using PivotTables for better asset insights

📂 Features & Functionalities
1️⃣ Structured Asset Inventory Sheet
Includes essential asset details:
Category (Laptop, Server, Printer, etc.)
Manufacturer & Model
Purchase & Warranty Expiry Dates
Status (In Use, Under Maintenance, Retired)
Assigned User & Location
2️⃣ Data Validation & Drop-Down Menus
Ensures consistent data entry with predefined lists.
Reduces manual errors in asset classification.
3️⃣ Automated Warranty Expiration Tracking
Red highlight for expired warranties.
Yellow warning for assets expiring within 90 days.
Uses the formula:
excel
Copy
Edit
=D2<TODAY()  → (Red for expired)  
=AND(D2>=TODAY(), D2<=TODAY()+90) → (Yellow for expiring soon)
4️⃣ Asset Lifecycle Workflow
Tracks assets through Requisition → Purchase → In Use → Retirement.
Ensures proper lifecycle documentation for audits.
5️⃣ Dynamic Reporting with PivotTables
Total assets by category & location.
Assets nearing warranty expiration.
Filtering based on asset status & department.
📌 Key Skills Demonstrated
🚀 Excel Data Management & Organization
🚀 Data Validation & Input Standardization
🚀 Conditional Formatting Automation
🚀 PivotTables for Data Analysis & Reporting
🚀 IT Asset Lifecycle & Tracking Knowledge

📎 Future Enhancements
🔹 Implement Power BI dashboards for advanced analytics.
🔹 Automate data updates using Excel Macros & VBA Scripts.
🔹 Integrate with Google Sheets API or SQL Database for cloud access.

💾 How to Use the IT Asset Tracking Sheet
1️⃣ Download the Excel file from this repository.
2️⃣ Open in Microsoft Excel (or Google Sheets).
3️⃣ Enter your organization’s asset details in the structured columns.
4️⃣ Use drop-downs for quick data entry.
5️⃣ Check conditional formatting to monitor warranty status.
6️⃣ Refresh PivotTables for updated asset insights.
