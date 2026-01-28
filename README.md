<div align="center">

# 📊 National Aadhaar Enrollment Analysis Dashboard
**Strategic Decision-Support System | UIDAI Data Hackathon**

[![Live Dashboard](https://img.shields.io/badge/View-Live_Dashboard-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrljoiYmlwZWU3Y2ItNDc5OC00Y2U2LTg3MjMtZmU1Yjc4NGI0ZjU0liwidCI6IjRhNzhmOWQwLWFIZGUtNDBjNC1hMDg4LTBIOTg5NTk5M2M0YSJ9)
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/data-analyst-harsh-soni)

</div>

---

## 🎯 Problem-Solution Analysis

| Challenge | Solution Provided |
| :--- | :--- |
| [cite_start]**Data Fragmentation:** Records spread across multiple files[cite: 14]. | [cite_start]**Centralized View:** Consolidated master dataset using Power Query[cite: 17, 87]. |
| [cite_start]**Operational Pressure:** Centers face sudden, unmanaged crowding[cite: 19]. | [cite_start]**Pressure Classification:** Categorized periods into Low to Extreme pressure[cite: 29, 179]. |
| [cite_start]**Age-Group Visibility:** Unclear which groups drive demand[cite: 22, 23]. | [cite_start]**Demographic Segmentation:** Revealed 0-5 years as the dominant group[cite: 27, 246]. |
| [cite_start]**Inefficient Allocation:** Uniform resource distribution regardless of demand[cite: 32, 33]. | [cite_start]**Regional Insights:** District-wise pressure analysis for targeted scaling[cite: 38, 51]. |

---

## 🖼️ Dashboard Gallery
*High-fidelity analytical modules for national-level decision support.*

<div align="center">

| 📈 Executive Summary | 👶 Demographic Deep-Dive |
|---|---|
| <img src="Dashboard/02_National_Academic_Dashboard_Executive_Summary.png" width="450"> | <img src="Dashboard/03_Application_and_Age_Wise_Enrollment_Analysis.png" width="450"> |
| *Macro KPIs & National Performance* | *Age-group dominance & population structure* |

| 🗺️ Regional Pressure Map | 🎓 Student Enrollment |
|---|---|
| <img src="Dashboard/04_Gender_and_Regional_Enrollment_Analysis.png" width="450"> | <img src="Dashboard/05_National_Student_Enrollment_Details.png" width="450"> |
| *Geospatial demand hotspots* | *Institutional tracking & academic data* |

</div>

---

## 🔄 Technical Workflow
[cite_start]The data was processed through a structured ETL pipeline to ensure consistency and reliability[cite: 98].

```mermaid
graph LR
    A[Raw CSV Data] --> B{Power Query ETL}
    B --> C[Cleaning & Normalization]
    C --> D[DAX Feature Engineering]
    D --> E[Interactive Dashboard]
    
    style A fill:#E1F5FE,stroke:#01579B,stroke-width:2px
    style B fill:#FFF9C4,stroke:#FBC02D,stroke-width:2px
    style C fill:#E8F5E9,stroke:#2E7D32,stroke-width:2px
    style D fill:#F3E5F5,stroke:#7B1FA2,stroke-width:2px
    style E fill:#F2C811,stroke:#000,stroke-width:4px
