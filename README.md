<div align="center">

# 📊 UIDAI Aadhaar Enrollment Analysis Dashboard
**Transforming Complex Government Data into Actionable Insights**

[![Status](https://img.shields.io/badge/Hackathon-UIDAI_Data_2024-orange?style=for-the-badge)](https://event.data.gov.in)
[![Tool](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)](https://github.com/your-username)

---

[Explore the Dashboard](#-dashboard-highlights) • [Key Insights](#-key-insights) • [Tech Stack](#-tools--technologies) • [Contact](#-about-the-author)

</div>

## 📖 Project Overview
This project was engineered for the **UIDAI Data Hackathon**. The objective was to solve the challenge of "Data Abundance but Insight Scarcity." By processing massive Aadhaar datasets, I built a visual ecosystem that identifies operational bottlenecks and demographic trends across India.

> **Status:** 🟢 Project Complete / ⏳ Hackathon Result Pending

---

## 🎯 The Problem & Solution

### **The Problem**
Aadhaar data is high-volume and fragmented. Decision-makers struggle to:
* Pinpoint which states are under **maximum operational pressure**.
* Understand if enrollment centers are reaching the **0-5 age demographic** effectively.
* Distinguish between organic growth and **policy-driven spikes**.

### **The Solution**
A high-performance Power BI dashboard utilizing **Advanced ETL** and **DAX measures** to provide a 360-degree view of the enrollment lifecycle.

---

## 🛠 Tools & Technologies
| Category | Tools | Application |
| :--- | :--- | :--- |
| **Visualization** | **Power BI** | Interactive UI/UX and spatial mapping |
| **Data Engine** | **Power Query** | Automated ETL & Data Cleaning |
| **Analytics** | **DAX (Data Analysis Expressions)** | Calculated KPIs like *Enrollment Momentum* |
| **Source** | **CSV / Open Data** | Sourced from [Data.gov.in](https://event.data.gov.in) |

---

## 🔄 Technical Workflow

```mermaid
graph LR
A[Raw CSV Data] --> B{Power Query ETL}
B --> C[Data Cleaning & Normalization]
C --> D[DAX Feature Engineering]
D --> E[Interactive Dashboard]
