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

## 📸 Dashboard Preview

### 🩺 Dashboard 1: Patient & Medical Overview
<p align="center">
  <img src="Screenshot 2025-11-21 222625.png" alt="Patient & Medical Dashboard" width="900"/>
</p>

### 💵 Dashboard 2: Financial & Operational Performance
<p align="center">
  <img src="Screenshot 2025-11-21 222720.png" alt="Financial Dashboard" width="900"/>
</p>

---

## 🧪 Data Processing Workflow

### 🔹 1. Data Cleaning (Power Query)
Raw data was transformed to create essential analytical columns:

- **Length of Stay:** Calculated days between `Admission Date` and `Discharge Date` to evaluate operational efficiency.
- **Test Result Flag:** Converted text results into binary logic (`Normal=1`, `Abnormal=0`) to calculate test accuracy rates.
- **Billing Category:** Segmented billing amounts into **Low**, **Medium**, and **High** for financial grouping.
- **Age Group:** Categorized patients into demographics (`0–18`, `19–35`, `36–60`, `60+`) to identify high-risk groups.

---

## 📈 Key Insights & Analysis

### 🌍 **1. Patient Demographics & Trends**
- **High-Risk Age Groups:** The analysis reveals which age brackets require the most medical attention, helping in resource allocation.
- **Admission Trends:** Monthly breakdown shows peak admission periods, allowing for better staff scheduling.

### 🔬 **2. Medical Test Performance**
- **Abnormal Test Rates:** Identified specific medical conditions that yield the highest percentage of "Abnormal" results.
- **Lab Efficiency:** Tracked "Pending" test results to measure the operational speed of laboratory processing.

### 🏥 **3. Hospital & Doctor Performance**
- **Patient Load:** Visualized which doctors and hospitals handle the highest volume of patients.
- **Operational Bottlenecks:** Correlated "Average Length of Stay" with specific conditions to see which treatments prolong hospitalization.

### 💰 **4. Financial & Insurance Analysis**
- **Revenue Drivers:** Identified top revenue-generating medical conditions.
- **Insurance Coverage:** Analyzed which insurance providers cover the highest billing amounts versus those with lower payouts.

---

## 📊 Results & Recommendations

### ✅ Key Results (KPIs)
| Metric | Description |
|:---|:---|
| **Total Patients** | Total number of unique admissions analyzed. |
| **Avg Length of Stay** | Key indicator of hospital efficiency and patient turnover speed. |
| **Abnormal Test Rate** | Percentage of tests returning abnormal results (indicating higher medical severity). |
| **Total Revenue** | Aggregated billing amount across all hospitals and conditions. |
| **Most Common Condition** | The medical condition with the highest frequency of admissions. |

### 💡 Strategic Recommendations

#### 1. Operational Efficiency
- **Reduce Pending Tests:** The data indicates a lag in test results for specific conditions. Streamlining lab communication could reduce the "Pending" rate and speed up discharge.
- **Optimize Bed Occupancy:** Conditions with an unusually high "Average Length of Stay" should be reviewed to see if process improvements can reduce patient time in-hospital.

#### 2. Financial Optimization
- **Focus on High-Value Insurance:** Strengthen relationships with the top 3 insurance providers identified in the "Billing by Insurance" chart, as they contribute the majority of revenue.
- **Billing Category Review:** Analyze the "Low" billing category to ensure no services are being undercharged compared to market rates.

#### 3. Resource Allocation
- **Staffing for Peak Months:** Based on the admission trend line, increase nursing and doctor staff during peak months (identified in the Time Analysis visuals) to handle patient influx.

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
