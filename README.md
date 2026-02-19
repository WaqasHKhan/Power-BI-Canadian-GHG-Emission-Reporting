# 🌎 Calgary GHG & Energy Use Analysis (2000–2018)

A full end‑to‑end data analytics project analyzing **Calgary’s greenhouse gas (GHG) emissions** and **energy consumption** from **2000 to 2018**.  
This project demonstrates advanced skills in **data cleaning**, **data modeling**, **DAX**, **Power BI dashboarding**, and **technical storytelling**.

---

## 📌 Project Overview

Canada’s commitment to the **Paris Agreement**, rising **carbon taxes**, and increasing **GHG emissions** make energy analytics more important than ever.  
This project transforms raw, inconsistent government datasets into a unified analytical model that reveals:

- Long‑term GHG emission trends  
- Energy consumption patterns by source  
- Sector‑level contributions  
- Calgary‑specific insights  
- Key performance indicators (KPIs) for policymakers  

The final deliverables include:

- Cleaned & consolidated datasets  
- A Power BI semantic model  
- DAX‑powered KPIs & metrics  
- Interactive dashboards  
- A professional presentation deck  

---

## 📊 1. Data Flow Diagram (DFD)

This diagram shows the full analytical workflow — from raw Excel files to Power BI dashboards.

<p align="center">
  <img src="diagrams/dfd.svg" width="90%" />
</p>

---

## ⭐ 2. Power BI Star Schema

The semantic model is built around **three core tables**:

- **Energy Use by Energy Source (PJ)**  
- **GHG Emissions by Energy Source**  
- **Total Energy & GHG Growth (2000–2018)**  

<p align="center">
  <img src="diagrams/star-schema.svg" width="90%" />
</p>

---

## 🧹 Data Cleaning & Standardization

All raw Excel files were cleaned and standardized using Excel and Power Query.

### ✔ Cleaning Steps
- Removed duplicates, blanks, and corrupted rows  
- Standardized column names and formats  
- Converted energy units (PJ → GJ → kWh)  
- Normalized sector and source categories  
- Aligned year fields across all datasets  
- Validated numerical ranges and totals  

### ✔ Consolidated Tables Produced
- `Energy_Use_By_Source_Clean.xlsx`  
- `GHG_Emissions_By_Source_Clean.xlsx`  
- `Total_Energy_GHG_Growth.xlsx`  

These tables form the foundation of the Power BI model.

---

## 🧠 Data Modeling (Power BI)

The Power BI model includes:

### **✔ One‑to‑One Relationship**
- **Energy Use by Source ↔ GHG Emissions by Source**

### **✔ Many‑to‑Many Relationship**
- **Total Energy & GHG Growth ↔ Source/Sector tables**

### **✔ Additional Modeling**
- Custom **Date Table**  
- Hierarchies (Year → Source → Sector)  
- Referential integrity checks  
- Data categories & formatting  

---

## 📐 DAX Measures

A robust DAX layer powers all KPIs and dashboards.

### **Unit Conversions**
- PJ → GJ  
- GJ → kWh  
- Emission intensity per unit of energy  

### **KPI Measures**
- `Total GHG Emissions`
- `Total Energy Consumption`
- `YoY % Change`
- `Energy Growth %`
- `GHG Growth %`
- `Emission Intensity`
- `Sector Contribution %`

### **Analytical Measures**
- Rolling averages  
- Trend indicators  
- Normalized metrics  

---

## 📊 Dashboards & Visuals

The Power BI report includes:

### **1. Executive KPI Dashboard**
- Total GHG emissions  
- Total energy consumption  
- Growth since 2000  
- Emission intensity trends  

### **2. Energy Source Analysis**
- Electricity  
- Natural gas  
- Motor gasoline  
- Oil  
- Aviation fuels  
- Wood waste & pulping liquor  

### **3. Sectoral Emissions**
- Residential  
- Commercial & Institutional  
- Industrial  
- Transportation  
- Agriculture  

### **4. Calgary‑Focused Insights**
- Localized trends  
- Policy implications  
- Carbon tax impact  
- Paris Agreement alignment  

---

## 🎤 Final Presentation

A polished PowerPoint deck summarizes:

- Project scope  
- Business problem  
- Data transformation  
- Key insights  
- Policy implications  
- Recommendations  

This presentation is designed for **executive and academic audiences**.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Excel** | Cleaning, standardization, consolidation |
| **Power BI** | Modeling, DAX, dashboards |
| **DAX** | KPIs, calculations, time intelligence |
| **GitHub** | Documentation & version control |

---

## 🚀 Key Outcomes

- Built a **fully automated analytical model** for 18 years of Calgary energy & GHG data  
- Delivered **interactive dashboards** for decision‑makers  
- Standardized and consolidated multiple messy datasets  
- Applied **advanced DAX** for KPIs and time‑series analysis  
- Produced a professional **presentation** for academic evaluation  
- Demonstrated strong **data engineering + BI storytelling** skills  

---

## 🙌 Author

**Waqas Ahmed**  
Senior Data Analyst | Business Intelligence | Power BI | SQL | Python  
Calgary, Alberta, Canada  

---

## ⭐ Explore the Dashboard

The Power BI file is included in the `/powerbi` folder.  
You can download and open it in **Power BI Desktop**.



