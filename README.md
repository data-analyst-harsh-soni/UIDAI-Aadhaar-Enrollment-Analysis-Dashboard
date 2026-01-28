<div align="center">

# 📊 National Aadhaar Enrollment Analysis Dashboard
**A Data-Driven Decision Support System for UIDAI Data Hackathon**

[![Hackathon](https://img.shields.io/badge/Hackathon-UIDAI_Data_2024-orange?style=for-the-badge)](https://event.data.gov.in)
[![Tool](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)](https://github.com/data-analyst-harsh-soni)

---

[Live Dashboard](https://app.powerbi.com/view?r=eyJrljoiYmlwZWU3Y2ItNDc5OC00Y2U2LTg3MjMtZmU1Yjc4NGI0ZjU0liwidCI6IjRhNzhmOWQwLWFIZGUtNDBjNC1hMDg4LTBIOTg5NTk5M2M0YSJ9) • [Problem-Solution](#-problem-solution-analysis) • [Technical Workflow](#-technical-workflow) • [Key Insights](#-key-insights) • [Contact](#-about-the-creator)

</div>

## 📖 Project Overview
[cite_start]This project transforms fragmented Aadhaar enrollment records into actionable insights to support government planning and resource allocation[cite: 42, 45]. [cite_start]Developed for the **UIDAI Data Hackathon**, the dashboard identifies enrollment demand patterns, operational pressure regions, and demographic dominance across India[cite: 46].

> [cite_start]**Project Goal:** To shift from reactive decision-making to a data-driven approach for inclusive growth[cite: 484].

---

## 🎯 Problem-Solution Analysis
| Challenge | Solution Provided |
| :--- | :--- |
| [cite_start]**Data Fragmentation:** Records spread across multiple files[cite: 14]. | [cite_start]**Centralized View:** Consolidated master dataset using Power Query[cite: 17]. |
| [cite_start]**Operational Pressure:** Centers face sudden, unmanaged crowding[cite: 19]. | [cite_start]**Pressure Classification:** Categorized periods into Low to Extreme pressure[cite: 29]. |
| [cite_start]**Age-Group Visibility:** Unclear which groups drive demand[cite: 23]. | [cite_start]**Demographic Segmentation:** Revealed 0-5 years as the dominant group[cite: 27]. |
| [cite_start]**Inefficient Allocation:** Uniform resource distribution regardless of demand[cite: 33]. | [cite_start]**Regional Insights:** State/District-wise pressure analysis for targeted scaling[cite: 38]. |

---

## 🛠 Tools & Technologies
* [cite_start]**Power BI:** Primary platform for visualization and interactive UI[cite: 127].
* [cite_start]**Power Query:** Used for the ETL layer (Extract, Transform, Load) to clean and standardize data[cite: 133].
* [cite_start]**DAX (Data Analysis Expressions):** Engineered complex KPIs such as *Enrollment Momentum* and *Demand Pressure*[cite: 136].
* [cite_start]**Government Open Data:** Sourced from `event.data.gov.in`[cite: 138].

---

## 🔄 Technical Workflow
[cite_start]The data was processed through a structured ETL pipeline to ensure reliability and accuracy[cite: 98].

```mermaid
graph LR
    A[Raw CSV Data] --> B{Power Query ETL}
    B --> C[Cleaning & Normalization]
    C --> D[DAX Feature Engineering]
    D --> E[Interactive Dashboard]
    
    style A fill:#f9f,stroke:#333
    style E fill:#00ff00,stroke:#333
