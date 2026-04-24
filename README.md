# Automated Inventory Management System (Excel-Based)

## 📌 Project Overview
This project is a comprehensive, automated solution designed to help Small and Medium Enterprises (SMEs) manage their inventory across multiple locations with precision. By leveraging advanced Excel functions and data modeling, the system transforms raw transaction data into actionable business insights, ensuring that stock-outs are prevented and warehouse value is accurately tracked.

## 🚀 Key Features
* **Multi-Site Tracking:** Manage and monitor stock levels across different branches (e.g., Store A, Store B, Store C) from a single interface.
* **Dynamic Transaction Engine:** A centralized log to record all stock movements (Receipts, Sales, and Opening Stock) using positive/negative quantity logic.
* **Real-Time Quantity on Hand (QoH):** Automated calculation of current stock levels based on historical transactions using optimized formulas.
* **Smart Reorder Alert System:** An automated logic that triggers a "Yes" alert when stock levels fall below the predefined **Reorder Level**, preventing operational delays.
* **Automated Purchase Orders:** A dedicated section powered by Pivot Tables and Slicers to filter required orders by Supplier instantly.
* **Visual Stock Reporting:** Interactive reports utilizing **Conditional Formatting** to highlight low-stock items in Red, enabling immediate visual detection.
* **Financial Insight:** Real-time calculation of total **Stock Value** to assist in financial reporting and auditing.

## 🛠️ Technical Stack
* **Data Modeling:** Advanced use of `SUMIFS`, `XLOOKUP`, and `IF` logic to link Transactions to Inventory Summaries.
* **Data Validation:** Implemented drop-down menus to ensure data integrity and prevent manual entry errors.
* **Pivot Tables & Slicers:** Used for dynamic filtering and creating a user-friendly interface for suppliers and orders.
* **Conditional Formatting:** Applied for data visualization and proactive inventory monitoring.

## 📂 System Components
1.  **Product Master Data:** Contains product IDs, names, cost per unit, and safety stock levels.
2.  **Transactions Log:** The "Engine" where every entry/exit is recorded with a unique Transaction ID.
3.  **Inventory Summary:** The core analysis sheet calculating total receipts, sales, and current balances per site.
4.  **Order Dashboard:** A refined view for managers to see exactly what needs to be ordered and from which supplier.

## 📈 Business Impact
This system eliminates the need for manual stock counting and reduces human error. By providing a "Visual First" approach to data, business owners can make faster decisions, optimize their cash flow by not over-ordering, and ensure they never miss a sale due to unexpected stock-outs.

---
**Developed by:** Abdelrahman Yakout  
**Role:** Data Analyst / Excel Solutions Developer
