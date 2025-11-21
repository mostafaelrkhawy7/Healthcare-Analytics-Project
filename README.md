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
  <img src="Screenshot 2025-11-21 222720.png" alt="Patient & Medical Dashboard" width="900"/>
</p>

### 💵 Dashboard 2: Financial & Operational Performance
<p align="center">
  <img src="Screenshot 2025-11-21 222625.png" alt="Financial Dashboard" width="900"/>   \
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

## 📈 Deep Dive Insights (Answering Key Questions)

### 🌍 **1. Patient Demographics & Medical Conditions**
* **Demographic Distribution:** The analysis identifies the **Age Group [Insert Dominant Group, e.g., 36-60]** as the most frequent visitors to the hospital.
* **Age-Condition Correlation:** There is a strong correlation between age and medical complexity; older age groups (60+) show a higher prevalence of chronic conditions requiring longer stays, whereas the 0-18 group is mostly associated with acute, short-term admissions.
* **Prevalent Conditions:** **[Insert Top Condition Name]** is the most common medical reason for admission, followed closely by **[Insert Second Condition]**.

### 🔬 **2. Test Results & Diagnostic Accuracy**
* **Test Outcomes:** The data shows that **[Insert %]** of all tests return "Normal" results. However, a critical **[Insert %]** are "Abnormal," highlighting the severity of the patient mix.
* **Operational Efficiency:** A significant percentage of tests (**[Insert %]**) remains "Pending." This bottleneck is highest in the **[Insert Month or Department]**, directly impacting patient discharge times.
* **Highest Abnormal Rates:** The medical condition **[Insert Condition Name]** consistently shows the highest rate of abnormal test results, indicating a need for specialized diagnostic equipment for these cases.

### 🏥 **3. Hospital & Doctor Performance**
* **Workload Analysis:** **Dr. [Insert Name]** handles the highest caseload among all staff. Simultaneously, **[Insert Hospital Name]** receives the largest inflow of patients, acting as the primary care hub.
* **Performance Metrics:** While some doctors handle high volumes, the analysis of "Abnormal Rates" per doctor helps distinguish between routine checkups and complex case management.

### 💰 **4. Financial Performance & Cost Trends**
* **Billing Analysis:** The total billing revenue for the period is **$[Insert Total]**, with an average cost per patient of **$[Insert Avg]**.
* **Cost Drivers:** The conditions generating the highest revenue are **[Insert Condition]**, while emergency admissions prove to be significantly more expensive on average compared to elective ones.
* **Insurance Insights:** **[Insert Provider Name]** is the most utilized insurance provider. However, **[Insert Provider Name]** covers the highest billing amounts per claim, making it the most valuable financial partner.

### ⏳ **5. Time-Based Operational Trends**
* **Peak Periods:** Patient inflow and billing amounts spike significantly during **[Insert Month]**, suggesting a seasonal pattern (e.g., winter flu season or year-end checkups).
* **Length of Stay:** The average length of stay is **[Insert Days]** days. Conditions such as **[Insert Condition]** require hospitalization well above the average, impacting bed turnover rates.

---

## 📊 Strategic Results & Recommendations

### ✅ Key Outcomes
| Metric | Result | Impact on Business |
|:---|:---|:---|
| **Top Revenue Source** | **[Condition Name]** | Focus marketing and equipment upgrades here. |
| **Highest Cost Efficiency** | **[Hospital Name]** | Model for operational best practices. |
| **Lab Bottleneck** | **Pending Rate > [X]%** | Delays discharge; requires process optimization. |
| **Top Insurance** | **[Provider Name]** | Priority for contract renewal and relationship management. |

### 💡 Recommendations
1.  **Resource Allocation:** Increase nursing staff and lab technicians during **[Peak Month]** to handle the identified surge in patient inflow and reduce the "Pending Test" rate.
2.  **Financial Strategy:** Review the billing structure for **[Lowest Revenue Condition]** as it consumes resources with minimal financial return.
3.  **Operational Improvement:** Investigate the discharge process for **[Condition with High LOS]** to reduce the Average Length of Stay and improve bed availability.

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
