# Microsoft Fabric Vehicle Lending BI Project 🚗📊

This end-to-end business intelligence project simulates a vehicle loan platform using Microsoft Fabric and Power BI. It demonstrates robust data engineering, dimensional modeling, semantic design, and interactive dashboards.

---

## 🚧 Current Status: Work in Progress  
- ✅ Data Engineering complete (Bronze → Silver → Gold)  
- ✅ Fact and Dimension tables created in Fabric Lakehouse  
- ✅ ER Diagram finalized  
- 🔜 Semantic model & DAX measures in progress  
- 🔜 Power BI reports being built and formatted  

---

## 🧱 Tech Stack
- **Microsoft Fabric** (Lakehouse, Notebooks, SQL, OneLake)
- **Power BI** (Import Mode, Semantic Model, DAX)
- **Delta Lake** (Parquet format for Silver & Gold layers)
- **Python & PySpark** (for transformation notebooks)

---

## 🗂️ Project Structure

/
├── architecture 
│ ├── power bi reports layout  # Diagrams of Power BI reports
│ └── erd.png # Final ER diagram with dimensions & facts
├── data
│ ├── bronze/ # Raw CSVs
│ ├── silver/ # Cleaned Parquet files
│ └── gold/ # Final tables (SQL-based)
│
├── notebooks/ # Fabric notebooks for cleaning and prep
├── powerbi/ # [Coming Soon] .pbix file + screenshots
├── semantic_models/ # [Coming Soon] Semantic model with DAX measures
└── README.md # Project overview (this file)

---

## 📌 Features

- Structured **Bronze → Silver → Gold** Lakehouse pipeline  
- Fact & Dimension modeling based on vehicle loan lifecycle  
- ERD built with full attribute and relationship coverage  
- Planned **DAX-based semantic model** for KPIs like NPA %, Early Closures  
- **Interactive Power BI dashboards** (Executive, Branch, Risk, Forecast)

---

## 📷 Screenshots (Coming Soon)

- ✅ Lakehouse and Fabric Notebook Views  
- 🟡 Power BI Report Pages  
- 🟡 Semantic Model Overview

---

Stay tuned — final dashboards and GitHub polish coming soon!

