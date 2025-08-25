# 🏭 Manufacturing-UA  
**Summer Internship Project | Data Automation using Microsoft Fabric**

---

## 📌 Introduction  
**Un-Available** is a Vietnam-based garment manufacturer established in 2004, producing for leading global streetwear and fashion brands.  

In early 2023, CEO **Paul Norriss** launched the **INNOVATION** team to **empower employees through data**. One of the team’s major projects was **automating KPI calculations** at individual, team, and company levels using **Microsoft Fabric**.  

My focus was on the **Commercial** and **Purchase** teams, which directly **generate and cost revenue**.  
> ⚠️ **Note:** All data shown here is mock data for demonstration purposes due to confidentiality.

---

## 🛠 Project Approach  

1. **Understand Client Expectations** → Define goals, pain points, and desired outcomes.  
2. **Analyze Current Process** → Document workflows, tools, and stakeholders.  
3. **Reperform & Validate** → Walk through the process to identify inefficiencies.  
4. **Identify Automation Opportunities** → Separate manual vs. automatable tasks.  
5. **Select Tools & Technologies** → Choose the best-fit solutions based on business needs.  
6. **Build Automated Solution** → Develop scripts, pipelines, and workflows.  
7. **Test Thoroughly** → Validate with real data for accuracy and robustness.  
8. **Deploy** → Move to production with proper controls and versioning.  
9. **Deliver to Client** → Provide the final solution with full documentation.  
10. **Train End Users** → Conduct workshops and provide user guides for adoption.

---

## 🧩 Solution Architecture — Microsoft Fabric  

This project implements a **medallion architecture** using **Microsoft Fabric**:

| **Layer** | **Purpose** | **Tools** | **Output** |
|-----------|------------|-----------|-----------|
| **Bronze** | Raw data ingestion | OneLake | Store original `.xlsx`, `.csv`, `.xls` |
| **Silver** | Data cleaning & transformation | PySpark Notebooks | Dimension & fact tables, Delta tables |
| **Gold** | Business-ready data | Delta Lake | Curated datasets for KPIs & reporting |

### **Visualization**
- Connected curated **Gold** data directly to **Power BI** for interactive dashboards.
- Provided **real-time KPI tracking** across individuals, teams, and departments.

---

## 🚀 Key Highlights  
- Designed a **scalable data pipeline** on **Microsoft Fabric**.  
- Automated KPI calculations for Commercial & Purchase teams.  
- Delivered **dynamic Power BI dashboards** for business insights.  
- Reduced manual reporting effort, improving data accuracy and speed.

---

## 🛠 Tech Stack  
- **Platform:** Microsoft Fabric (OneLake, Medallion Architecture)  
- **Data Processing:** PySpark, Notebooks  
- **Visualization:** Power BI   

---
