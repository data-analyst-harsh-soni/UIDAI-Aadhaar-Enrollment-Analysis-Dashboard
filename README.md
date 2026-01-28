<div align="center">

# 📊 National Aadhaar Enrollment Analysis Dashboard
**Strategic Decision-Support System | UIDAI Data Hackathon**

[![Live Dashboard](https://img.shields.io/badge/View-Live_Dashboard-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiOTkxYTVmN2ItNWViOC00ZDY5LWFmYTMtZjU3MjE4ZGJmYzM5IiwidCI6IjRhNzhmOWQwLWFiZGUtNDBjNC1hMDg4LTBiOTg5NTk5M2M0YSJ9&pageName=5e484e6a688e60e79c50)
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/data-analyst-harsh-soni)

---

[Live Demo Link](https://app.powerbi.com/view?r=eyJrIjoiOTkxYTVmN2ItNWViOC00ZDY5LWFmYTMtZjU3MjE4ZGJmYzM5IiwidCI6IjRhNzhmOWQwLWFiZGUtNDBjNC1hMDg4LTBiOTg5NTk5M2M0YSJ9&pageName=5e484e6a688e60e79c50) • [The Problem](#-problem-solution-analysis) • [Technical Workflow](#-technical-workflow) • [Dashboard Gallery](#-dashboard-gallery) • [Key Insights](#-key-insights) • [Contact](#-about-the-creator)

</div>

## 📖 Project Overview
[cite_start]Developed for the **UIDAI Data Hackathon**, this project transforms fragmented Aadhaar enrollment data into a unified decision-support dashboard[cite: 6, 42]. [cite_start]By processing massive datasets, I built a visual ecosystem to identify enrollment patterns, operational pressure, and demographic drivers[cite: 42, 46].

> [cite_start]**Status:** 🟢 Project Complete / ⏳ Hackathon Result Pending [cite: 6]

---

## 🎯 Problem-Solution Analysis
| [cite_start]Challenge [cite: 13, 18, 22, 32] | [cite_start]Solution Provided [cite: 17, 21, 27, 38] |
| :--- | :--- |
| **Data Fragmentation:** Records spread across multiple files. | **Centralized View:** Unified dataset created using Power Query. |
| **Operational Pressure:** Centers face sudden, unmanaged crowding. | **Pressure Classification:** Categorized into Low to Extreme pressure. |
| **Age-Group Visibility:** Unclear which groups drive demand. | **Demographic Segmentation:** Revealed 0-5 years as the dominant group. |
| **Inefficient Allocation:** Uniform distribution regardless of demand. | **Regional Insights:** State/District-wise pressure analysis for scaling. |

---

## 🖼️ Dashboard Gallery
[cite_start]*Visual representation of all 5 analytical modules developed in Power BI[cite: 213, 215, 216, 218, 220].*

<div align="center">

### [cite_start]1️⃣ Executive Summary [cite: 213]
[cite_start]Macro-view of total enrollments, success rates, and national trends[cite: 214].
<img src="Dashboard/National Aadhaar Enrollment – Executive Summary.png" width="900" alt="Executive Summary Dashboard">

---

### [cite_start]2️⃣ Operational & Regional Deep-Dive [cite: 215, 216]
| Activity Snapshot | State-wise Pressure Snapshot |
|---|---|
| <img src="Dashboard/Aadhaar Enrollment Activity Snapshot.png" width="450"> | <img src="Dashboard/State-wise Aadhaar Enrollment Pressure Snapshot.png" width="450"> |
| [cite_start]*Peak periods and recurring trends [cite: 217]* | [cite_start]*High and moderate pressure regions [cite: 215]* |

---

### [cite_start]3️⃣ Demographic & Trend Analysis [cite: 218, 220]
| Population & Age-wise Analysis | National Enrollment Analysis |
|---|---|
| <img src="Dashboard/Population & Age-wise Enrollment Analysis.png" width="450"> | <img src="Dashboard/National Aadhaar Enrollment Analysis.png" width="450"> |
| [cite_start]*Age-group dominance & structure [cite: 221]* | [cite_start]*Seasonality & momentum classification [cite: 219]* |

</div>

---

## 🔄 Technical Workflow
[cite_start]The data was processed through a structured ETL pipeline to ensure consistency and reliability[cite: 98, 115].



```mermaid
graph LR
    A[Raw CSV Data] --> B{Power Query ETL}
    B --> C[Cleaning & Normalization]
    C --> D[DAX Feature Engineering]
    D --> E[Interactive Dashboard]
    
    %% Styles for High Visibility %%
    style A fill:#B3E5FC,stroke:#01579B,stroke-width:2px,color:#000
    style B fill:#FFF9C4,stroke:#FBC02D,stroke-width:2px,color:#000
    style C fill:#C8E6C9,stroke:#2E7D32,stroke-width:2px,color:#000
    style D fill:#E1BEE7,stroke:#7B1FA2,stroke-width:2px,color:#000
    style E fill:#F2C811,stroke:#000,stroke-width:4px,color:#000
