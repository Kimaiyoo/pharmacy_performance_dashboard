# 🧾 Doctor Rx Performance & Conversion Dashboard

A Power BI dashboard project designed to track and visualize doctor prescription performance, brand competition, and conversion trends across regions and medical representatives.

---

## 📁 Project Overview

This dashboard is built using RCPA (Retail Chemist Prescription Audit) data to provide actionable insights into:

- Doctor Rx performance
- Brand competition across regions.
- Product Distribution per region.

---

## 🎯 Objectives

- Track **actual vs. target prescription performance** by brand, doctor, and region
- Evaluate **brand market share** and **competitive presence** per territory
- Identify **converted doctors** who consistently prescribe target brands
- Support strategic decision-making for medical representatives and managers

---

## 📊 Key Features

### 1. **Rx Performance vs. Target**
- Weekly actual Rx normalized against monthly targets
- Dynamic filtering by Brand, Region, and Med Rep

### 2. **Brand Competition Analysis**
- Stacked visuals comparing competitor and focus brands
- Region-wise segmentation of brand performance

### 3. **Doctor Conversion Tracking**
- A doctor is marked “Converted” if they meet or exceed target Rx in **3 consecutive RCPA visits**
- Conversion status visualized with filters and indicators

### 4. **Interactive Visuals**
- Slicers for:
  - Region
  - Medical Representative
  - Brand
  - Doctor Name
- Drill-down capabilities for detailed analysis

---

## 📂 Data Sources

- `JOTFORMS TRIAL v1.xlsx`: Source RCPA data from field audits
- Processed using **Power Query** for transformation, cleaning and modeling

---
---

## 📌 How to Use

1. Clone this repository or download the `.pbix` file
2. Open the Power BI report in **Power BI Desktop**
3. Refresh the data (linked to the Excel file)
4. Use slicers to filter insights by:
   - Region
   - Brand
   - Med Rep
   - Doctor

---

## 💡 Future Improvements

- Integrate monthly automation via Power BI Service or Power Automate
- Add forecasting & time-series analysis for longer-term trends
- Include segmentation by doctor specialty or clinic profile

---

## 👤 Author

**Naomi Jepkorir Kimaiyo**(https://github.com/Kimaiyoo)  
---

## 📄 License

This project is for educational and professional portfolio use. Contact the author for reuse in commercial settings.
