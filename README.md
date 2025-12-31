# 🏛️ Guggenheim Abu Dhabi Museum Dashboard
This advanced analytics project focuses on visualizing museum operations and visitor metrics for the Guggenheim Abu Dhabi. The dashboard was architected to handle complex dataset relationships, providing a centralized view of operational efficiency and visitor engagement.

**📄 View PDF Report:**  [Abu Dhabi Mesuem Dashboard.pdf](https://github.com/user-attachments/files/24394032/Abu.Dhabi.Mesuem.Dashboard.pdf)

## 🛠️ Tools & Technologies
* **Power BI:** Advanced visualization and reporting.
* **Star Schema Architecture:** Designed a robust data model with a central Fact table and surrounding Dimension tables to optimize query performance.
* **Complex DAX:** Engineered sophisticated measures to calculate visitor retention, peak hours, and capacity utilization.

## 📊 Key Features
* **Operational Efficiency:** Visualized ticket sales vs. actual attendance to measure capacity utilization.
* **Visitor Demographics:** Segmented visitor data to help marketing teams target under-represented audiences.
* **Performance Tracking:** Custom KPI gauges tracking current performance against quarterly targets.
* **Interactive Filtering:** Slicers allowing deep-dives by Date, Event Type, and Visitor Category.

## 🏗️ Data Model
The project utilizes a **Star Schema** design:
* **Fact Table:** `Daily Operations` containing transactional records.
* **Dimension Tables:** `Visitors`, `Events`, `Time`, and `Locations`.
This structure ensures fast report rendering and accurate drill-down capabilities.

## 📷 Dashboard Screenshot
 <img width="642" height="718" alt="Screenshot 2025-12-31 160104" src="https://github.com/user-attachments/assets/8433eebb-a444-4290-b901-ad106f8b2fa7" />
