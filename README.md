# Aviation Inventory Management System

### 📋 Project Overview
https://docs.google.com/spreadsheets/d/1ea7-MlE4MjqGKj4Wlft4CkI3ex-bsQaZh6c5NIHvSno/copy

This platform is a specialized data tool designed for aviation logistics. It manages a complex database of high-value components (Turbine Blades, Garmin Displays), transforming raw transaction logs into an executive-level command center

### Dashboard Preview
https://github.com/user-attachments/assets/3ad173c4-a9d4-488d-be45-4192e0464c07

### 🏗️ Core System Architecture
The system is built on a 4-tier relational structure to ensure data integrity:
* **Tier 1: Master Inventory (Source of Truth):** Defines static product data and safety stock thresholds.
* **Tier 2: Transaction Engine (Data Entry):** Captures historical movement with strict "In" vs "Issue" categorization.
* **Tier 3: Logic Processor (Back-end):** Handles the mathematical heavy lifting using advanced lookup and summation logic.
* **Tier 4: Executive Dashboard (Visualization):** Aggregates processed data into actionable KPI metrics for stakeholders.

### 🚀 Key Technical Features
* **Zero-State UI Logic:** Implemented `IF` and `IFERROR` gatekeepers to maintain a clean, blank interface when data is absent.
* **Dynamic Stock Valuation:** Real-time financial tracking that adjusts based on current closing stock and unit costs.
* **Automated Health Alerts:** Proactive 'REORDER' system triggered automatically when stock drops below safety levels.
* **Filtered Interactivity:** Utilizes `SUBTOTAL` logic to ensure KPI cards update instantly when using slicers.

### 🛠️ How To Use It
1.  **Register:** Add new parts to the *Master Inventory* sheet first.
2.  **Log:** Record all stock movements in the *Transaction Log* using the dropdown menus.
3.  **Monitor:** Check the *Inventory Engine* for real-time calculation accuracy.
4.  **Analyze:** Use the *Executive Dashboard* to view high-level stats and filter for specific items.
