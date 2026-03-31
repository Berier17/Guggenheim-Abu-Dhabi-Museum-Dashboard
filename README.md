# 🏛️ Guggenheim Abu Dhabi Museum Dashboard
This Power BI analytics dashboard is designed to monitor and optimize the document control and engineering drawing workflows for the Guggenheim Abu Dhabi construction project. It provides a centralized, data-driven view of the drawing review lifecycle, transforming complex project documentation logs into actionable insights for project managers, lead engineers, and executive stakeholders.

**📄 View PDF Report:**  [Abu Dhabi Mesuem Dashboard.pdf](https://github.com/user-attachments/files/24394032/Abu.Dhabi.Mesuem.Dashboard.pdf)

## 🛠️ Tools & Technologies
* **Power BI:** Advanced data visualization and operational reporting.
* **Star Schema Architecture:** Designed a robust data model with a central Fact table (Drawing Logs) and surrounding Dimension tables (Disciplines, Building Zones, Statuses) to optimize query performance.
* **DAX & Data Modeling:** Engineered sophisticated measures to calculate completion percentages, segment drawing scopes, and track approval workflows.

## 📊 Key Features
* **Scope Optimization Tracking:** Monitoring the distribution of drawings designated as "As-Built" versus those submitted with a "No Change" stamp.
* **Discipline & Area Analysis:** Segmenting drawing data across key disciplines like Architectural, Concrete General Arrangement, and Façade Systems, mapped against specific building zones.
* **Workflow Status Monitoring:** Visualizing document approval progress through stages such as "Approved," "Revise and Resubmit," and "Issued for Internal Review".
* **Usage Categorization:** Categorizing drawing delivery by functional usage, including Authority Approval, Contractual requirements, and Facility Management.

## 🏗️ Data Model
The project utilizes a **Star Schema** design tailored for construction management:
* **Fact Table:** `Drawing Register` containing transactional records of all submitted documents and their current review iterations.
* **Dimension Tables:** `Disciplines` (MEP, Civil, etc.), `Building Areas/Zones`, and `Review Statuses`. 
This structure ensures fast report rendering and allows project managers to easily drill down into specific engineering bottlenecks.


## 📷 Dashboard Screenshot
 <img width="642" height="718" alt="Screenshot 2025-12-31 160104" src="https://github.com/user-attachments/assets/8433eebb-a444-4290-b901-ad106f8b2fa7" />

