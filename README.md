# 🏥 Healthcare Analytics Dashboard

## 🧩 Project Overview
An interactive **Excel Healthcare Dashboard** designed to analyze patient statistics, medical test results, hospital performance, and financial metrics.  
The project transforms raw hospital data into a structured analytical model covering **Patient Demographics**, **Medical Test Accuracy**, **Operational Efficiency**, and **Financial Revenue**.

The analysis focuses on two main views:
1. **Patient & Medical Overview**
2. **Financial & Operational Performance**

---

## 🧰 Tools & Techniques
- **Microsoft Excel**
  - **Power Query** for advanced data cleaning and custom column creation
  - **Data Modeling** using relationships and derived tables
  - **Pivot Tables & Charts** for multi-dimensional analysis
  - **DAX-Style Measures** for calculating rates and KPIs
  - **Slicers & Timelines** for interactive filtering

---

## 🧪 Data Processing Workflow

### 🔹 1. Data Cleaning (Power Query)
Raw data was transformed to create essential analytical columns:

- **Length of Stay:** Calculated days between `Admission Date` and `Discharge Date` to evaluate operational efficiency.
- **Test Result Flag:** Converted text results into binary logic:
  - Normal → `1`
  - Abnormal → `0`
  - Pending → `BLANK`
- **Billing Category:** Segmented billing amounts into **Low**, **Medium**, and **High** for financial grouping.
- **Age Group:** Categorized patients into demographics: `0–18`, `19–35`, `36–60`, `60+`.
- **Time Intelligence:** Extracted Admission/Discharge **Months** and **Years** for trend analysis.

---

### 🔹 2. Data Modeling & Measures
Custom measures were created to track medical accuracy and financial health:

| Category | Measure | Formula / Logic |
|:---|:---|:---|
| **Medical** | **Completed Tests** | `= Normal Count + Abnormal Count` |
| **Medical** | **Normal Test Rate** | `= Normal Count / Total Tests` |
| **Medical** | **Abnormal Rate** | `= Abnormal Count / Total Tests` |
| **Medical** | **Pending Rate** | `= Pending Count / Total Tests` |
| **Financial** | **Total Billing** | Sum of all billing transactions |
| **Financial** | **Avg Billing** | Average cost per patient/visit |
| **Operational** | **Avg Length of Stay** | Average days a patient occupies a room |
| **Operational** | **Total Rooms** | Count of unique rooms utilized |

---

## 📊 Dashboard Insights

### 🩺 **1. Patient & Medical Overview**
Focused on demographics and medical conditions.
- **Demographics:** Analyzes which Age Groups visit the most and if age correlates with specific conditions.
- **Test Analysis:** Breakdown of **Normal vs. Abnormal vs. Pending** results.
- **Condition Analysis:** Identifies conditions with the highest "Abnormal" test rates.
- **Performance:** Tracks which Hospitals and Doctors handle the highest volume of cases.

---

### 💵 **2. Financial & Operational Performance**
Focused on revenue, costs, and insurance.
- **Cost by Condition:** Identifies which medical conditions generate the highest revenue vs. lowest cost.
- **Operational Efficiency:** Detailed view of **Average Length of Stay**; determines which conditions require longer hospitalization.
- **Time Trends:** Monthly and Yearly billing trends to identify peak financial periods.
- **Insurance Analysis:** Breakdown of top Insurance Providers by usage frequency and coverage amounts.

---

## 📸 Dashboard Preview
<p align="center">
  <img src="path-to-your-image.png" alt="Healthcare Dashboard Preview" width="900"/>
</p>

---

## 📎 Files Included
- `Healthcare.xlsm` — Complete Excel file with raw data, Power Query steps, Data Model, and final Dashboards.

---

## 🚀 How to Use
1. Open `Healthcare.xlsm` in Microsoft Excel.
2. Enable Macros/Content if prompted (for interactivity).
3. Navigate to the **Dashboard** tabs.
4. Use **Slicers** (Year, Hospital, Doctor, Condition) to filter the data dynamically.

---

## 👨‍💻 Author
**Mostafa Elrkhawy** Excel & BI Analyst  
📧 [LinkedIn Profile](https://www.linkedin.com/in/mostafa-elrkhawy/)  
📅 **Project Type:** Healthcare Data Analytics & Dashboarding
