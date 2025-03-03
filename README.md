# 📊 IT Asset Management & Tracking System  
**Efficient IT Asset Lifecycle Tracking Using Microsoft Excel**  

## 📌 Project Overview  
This project is a **structured IT asset tracking system** built using Microsoft Excel. It enables organizations to efficiently manage their **hardware and software inventory**, track **lifecycle stages**, and automate **warranty monitoring** with conditional formatting.  

✅ **Tracks IT assets from requisition to retirement**  
✅ **Standardizes data entry with validation & drop-down lists**  
✅ **Automates warranty expiration tracking with conditional formatting**  
✅ **Generates reports using PivotTables for better asset insights**  

## 📂 Features & Functionalities  

### 1️⃣ Structured Asset Inventory Sheet  
- Includes essential asset details:  
  - **Category** (Laptop, Server, Printer, etc.)  
  - **Manufacturer & Model**  
  - **Purchase & Warranty Expiry Dates**  
  - **Status** (In Use, Under Maintenance, Retired)  
  - **Assigned User & Location**  

### 2️⃣ Data Validation & Drop-Down Menus  
- Ensures **consistent data entry** with **predefined lists**.  
- Reduces manual errors in asset classification.  

### 3️⃣ Automated Warranty Expiration Tracking  
- **Red highlight** for **expired warranties**.   
- Uses the formula:  
  ```excel
  =D2<TODAY()  → (Red for expired)  
  =AND(D2>=TODAY(), D2<=TODAY()+90) → (Yellow for expiring soon)
