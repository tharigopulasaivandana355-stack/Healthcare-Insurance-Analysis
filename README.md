# 🏥 Healthcare Insurance Analytics Dashboard

## 📌 Project Overview
This project analyzes healthcare insurance claims data to uncover **cost drivers, utilization patterns, and risk segments**.  
It combines **Python (Jupyter Notebook)** for preprocessing & exploratory analysis with **Tableau** for interactive dashboards.

The notebook produces:
- Cleaned dataset with standardized fields
- Key performance indicators (KPIs)
- Visualizations of claims, costs, providers, and patient deductibles
- Tableau-ready CSV exports

---

## 🔑 Key Features
- **KPIs**: Total Paid by Insurance, Avg Paid per Claim, Number of Claims
- **Visualizations**:
  1. Total Paid by Insurance by **Provider Specialty** (highlighting top 2)
  2. **Monthly trend**: Commercial vs Medicare
  3. **Insurance Paid vs Patient Deductible** (scatter, ≤ $2,000, with trendline)
  4. **Quarterly spend by State** (bubble chart for top states)
- **Exports**: Clean summary CSVs for Tableau dashboards

---

## 📂 Repository Structure
```
Healthcare-Insurance-Analytics-Dashboard/
│── data/                          # Original dataset (Excel/CSV)
│── exports/                       # Clean CSVs for Tableau
│── tableau/                       # Tableau workbook (.twbx) + screenshots
│── Healthcare_Insurance_Analytics.ipynb   # Jupyter Notebook
│── README.md                      # Project description (this file)
```

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Healthcare-Insurance-Analytics-Dashboard.git
   cd Healthcare-Insurance-Analytics-Dashboard
   ```
2. Install requirements:
   ```bash
   pip install pandas matplotlib openpyxl
   ```
3. Place dataset in `data/ABC_Healthcare_Claims.xlsx`
4. Run the notebook:
   ```bash
   jupyter notebook Healthcare_Insurance_Analytics.ipynb
   ```
5. Open the Tableau workbook (`.twbx`) to explore dashboards.

---

## 📊 Tableau Dashboards
Screenshots of dashboards created in Tableau:

- **Executive KPIs**
- **Claims & Cost Drivers**
- **Denials & Workflow**
- **Member Segmentation**

*(add images from `tableau/` here)*

---

## 📚 Dataset
- **Source**: `ABC Healthcare Company Claims Dataset.xlsx`  
- Contains: Claim ID, Patient State, Product Line, Date of Service, CPT/Procedure details, Provider Specialty, Insurance Paid, Patient Deductible.

---

## 🙌 Acknowledgments
This project was inspired by open-source healthcare analytics repos and adapted with additional **Python preprocessing, visualizations, and Tableau dashboards**.
