# Hospital-Performance-Analysis

# Hospital Performance & Patient Outcomes Dashboard  

![Power BI](https://img.shields.io/badge/Built%20With-Power%20BI-yellow?style=for-the-badge&logo=powerbi)  
![Data Modeling](https://img.shields.io/badge/Data%20Model-Star%20Schema-blue?style=for-the-badge)  
![Domain](https://img.shields.io/badge/Domain-Healthcare-lightgrey?style=for-the-badge)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)  

---

## 🔹 Background & Overview  

Healthcare systems constantly balance clinical quality, operational efficiency, and financial sustainability. Hospitals, in particular, face increasing pressure to improve patient outcomes while managing rising treatment costs and optimizing resource utilization.  

This analysis was conducted using a hospital admissions dataset containing key information such as:  
- Patient demographics (age, gender, blood type)  
- Admission types (elective, urgent, emergency)  
- Length of stay (LOS)  
- Billing and insurance details  
- Test results and discharge outcomes  

The goal of this project was to translate raw hospital data into actionable insights that improve decision-making around patient flow, cost control, and care outcomes.  

---

## Executive Summary  

This dashboard delivers a comprehensive view of hospital performance, revealing how admission types, patient demographics, and treatment durations affect billing and discharge outcomes.  

**Key takeaways include:**  
- Elective admissions drive the majority of hospital revenue, showing longer average stays (15–30 days) and higher billing values ($200K–$350K).  
- Urgent admissions maintain a balance between care intensity and cost efficiency, clustering around mid-level billing ($100K–$200K) for moderate stays (5–15 days).  
- Emergency admissions are operationally critical but less profitable, typically short-stay (<15 days) and below $200K billing.  
- A strong positive correlation exists between Average Length of Stay (ALOS) and Total Billing, especially in planned admissions.  

These insights highlight opportunities to optimize financial performance without compromising quality of care, through targeted improvements in stay duration management and care pathways.  

---

## Insight Deep Dive  

### 1. Hospital Performance & Efficiency  
**Qualified Values:**  
- Average Length of Stay (ALOS): **15.71 days**  
- Average Billing per Patient: **$24.646.2k**  
- Discharge Rate: **97.66%**  

Comparing across admission types, elective cases have maintained stable LOS and billing over time, while urgent cases show variability — suggesting operational bottlenecks.  

---

###  2. Cost & Insurance Impact  
**Qualified Values:**  
- Top Insurance Provider covers **42%** of total hospital costs.  
- Elective procedures contribute **~60%** of total revenue despite fewer cases.  

High dependency on few insurers increases financial concentration risk. Diversifying insurance partnerships or negotiating cost-sharing models could improve revenue stability.  

---

## Recommendations  

### 1. Optimize Elective Admission Throughput  
Elective cases are profitable but resource-intensive. Introducing **Enhanced Recovery Protocols (ERP)** and **preoperative optimization** can shorten LOS while maintaining care quality.  

### 2. Enhance Emergency Care Efficiency  
Emergency admissions are vital for hospital reputation and patient safety. Implementing **Rapid Assessment Units (RAUs)** and **triage analytics** can reduce congestion and lower the cost per emergency episode.  

---

## Tech Stack  
- **Power BI** — Data visualization & dashboard creation  
- **Power Query** — Data transformation & cleaning  
- **DAX** — Calculated measures (ALOS, billing per patient, discharge %)  
- **Star Schema** — Data modeling for optimized relationships  
- **Excel / CSV** — Source dataset  

---

## Metrics Used  
- **Average Length of Stay (ALOS)**  
- **Total Billing & Billing per Patient**  
- **Discharge Rate**  
- **Top Insurance Provider Coverage %**  
- **Revenue by Admission Type**  

---

## Domain Knowledge  
Hospital performance analytics provides operational insights into **care efficiency**, **resource utilization**, and **financial sustainability**.  
By integrating **clinical, financial, and operational** dimensions, hospitals can shift from reactive reporting to **data-driven strategic planning**.  

---

## Contact  
If you’d like to connect or discuss similar healthcare analytics projects:  
**Author:** [Your Name Here]  
**Email:** [your.email@example.com]  
**LinkedIn:** [Your LinkedIn Profile]  

---
