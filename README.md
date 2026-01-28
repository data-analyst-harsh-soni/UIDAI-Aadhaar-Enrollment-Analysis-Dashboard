<div align="center">

# 📊 UIDAI Aadhaar Enrollment Analysis Dashboard
**Transforming Complex Government Data into Actionable Insights**

[![Status](https://img.shields.io/badge/Hackathon-UIDAI_Data_2024-orange?style=for-the-badge)](https://event.data.gov.in)
[![Tool](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)](https://github.com/data-analyst-harsh-soni)

---

[The Dashboard](#-dashboard-gallery) • [Technical Workflow](#-technical-workflow) • [Key Insights](#-key-insights) • [Contact](#-about-the-author)

</div>

## 📖 Project Overview
Developed for the **UIDAI Data Hackathon**, this project solves the challenge of "Data Abundance but Insight Scarcity." By processing massive Aadhaar datasets, I built a visual ecosystem that identifies operational bottlenecks and demographic trends across India.

> **Status:** 🟢 Project Complete / ⏳ Hackathon Result Pending

---

## 🖼️ Dashboard Gallery
*Visual representation of the analytical modules.*

| Executive Summary | Demographic Analysis |
|---|---|
| <img src="Dashboard/02_National_Academic_Dashboard_Executive_Summary.png" width="400"> | <img src="Dashboard/03_Application_and_Age_Wise_Enrollment_Analysis.png" width="400"> |

| Regional Insights | Student Enrollment |
|---|---|
| <img src="Dashboard/04_Gender_and_Regional_Enrollment_Analysis.png" width="400"> | <img src="Dashboard/05_National_Student_Enrollment_Details.png" width="400"> |

---

## 🔄 Technical Workflow
*The architecture of data transformation.*

```mermaid
graph LR
    A[Raw CSV Data] --> B{Power Query ETL}
    B --> C[Data Cleaning & Normalization]
    C --> D[DAX Feature Engineering]
    D --> E[Interactive Dashboard]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style E fill:#00ff00,stroke:#333,stroke-width:4px
