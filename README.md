# 📊 Production KPI Dashboard  
**Industrial Process Monitoring with Python & Streamlit**

---

## 🔷 Project Overview

This project presents an **interactive KPI dashboard for industrial production processes**, designed to monitor performance, quality, and process stability in real time.

Built using a manufacturing dataset adapted from the **AI4I 2020 Predictive Maintenance Dataset (Kaggle)**, the solution demonstrates how data can be transformed into actionable insights for plant engineers and decision-makers.

The dashboard enables:
- Monitoring of production efficiency
- Early detection of quality issues
- Analysis of process variables impacting defects

---

## 🎯 Business Objective

In industrial environments, large volumes of process data are generated but often underutilized.

This project aims to:
> Convert raw production and process data into **clear, actionable KPIs** that support operational decisions.

Key questions addressed:
- Are we producing efficiently?
- Is quality deteriorating?
- Which variables are driving defects?

---

## 🧠 Key Features

### 📊 KPI Monitoring
- Total production
- Defect rate (%)
- Failures by type

### 📈 Process Analysis
- Time-series trends of key variables
- Variability analysis (process stability)
- Relationship between process variables and defects

### 🔍 Interactive Filters
- Production line
- Product type
- Shift (A/B/C)

### ⚙️ Industrial Focus
- Inspired by real manufacturing environments
- Aligned with Lean Six Sigma and SPC principles

---

## 🗂️ Project Structure

```bash
02-production-kpi-dashboard/
├── data/
│   └── production_data.csv
├── app/
│   └── dashboard.py          # Streamlit dashboard
├── notebooks/
│   └── 01_kpi_analysis.ipynb # KPI validation and exploration
├── src/
│   └── kpi_functions.py      # Reusable KPI logic
├── README.md
└── requirements.txt