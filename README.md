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
  <img src="Screenshot%202025-11-21%20222625.png" alt="Patient & Medical Dashboard" width="900"/>
</p>

### 💵 Dashboard 2: Financial & Operational Performance
<p align="center">
  <img src="Screenshot%202025-11-21%20222720.png" alt="Financial Dashboard" width="900"/>
</p>

---

## 🧪 Data Processing Workflow

### 🔹 1. Data Cleaning (Power Query)
Raw data was transformed to create essential analytical columns:
- **Length of Stay:** Calculated days between `Admission Date` and `Discharge Date`.
- **Test Result Flag:** Converted text results into binary logic (`Normal=1`, `Abnormal=0`).
- **Billing Category:** Segmented billing into **Low**, **Medium**, and **High**.
- **Age Group:** Categorized patients into (`0–18`, `19–35`, `36–60`, `60+`).

---

### 🔹 2. Key Measures (KPIs) & Calculations
Advanced measures were created to ensure dynamic aggregation and accurate performance tracking.

#### 🩺 Medical Measures
| Measure | Formula / Logic | Purpose |
|:---|:---|:---|
| **Completed Tests** | `Normal Count + Abnormal Count` | Tracks total finalized lab tests. |
| **Normal Test Rate** | `Normal Count / Total Tests` | % of healthy results. |
| **Abnormal Test Rate** | `Abnormal Count / Total Tests` | Indicator of patient severity. |
| **Pending Test Rate** | `Pending Count / Total Tests` | Measures lab operational backlog. |
| **Abnormal From Completed** | `Abnormal / (Normal + Abnormal)` | True positive rate excluding pending cases. |

#### 💵 Financial Measures
| Measure | Formula / Logic | Purpose |
|:---|:---|:---|
| **Total Billing** | `SUM(Billing Amount)` | Total revenue generated. |
| **Average Billing** | `AVERAGE(Billing Amount)` | Cost per admission. |
| **Max/Min Billing** | `MAX/MIN(Billing Amount)` | Identifies outliers and cost range. |

#### 🏥 Operational Measures
| Measure | Formula / Logic | Purpose |
|:---|:---|:---|
| **Patient Count** | `DISTINCTCOUNT(Patient ID)` | Total unique admissions. |
| **Avg Length of Stay** | `AVERAGE(Length of Stay)` | Key efficiency metric for bed turnover. |
| **Total Rooms** | `COUNT(Room ID)` | Utilization capacity tracking. |

---

## 📈 Deep Dive Insights (Answering Key Questions)

### 🌍 **1. Patient Demographics & Medical Conditions**
* **Demographic Distribution:** The analysis identifies the **Age Group [Insert Dominant Group]** as the most frequent visitors to the hospital.
* **Age-Condition Correlation:** There is a strong correlation between age and medical complexity; older age groups (60+) show a higher prevalence of chronic conditions requiring longer stays.
* **Prevalent Conditions:** **[Insert Top Condition]** is the most common medical reason for admission.

### 🔬 **2. Test Results & Diagnostic Accuracy**
* **Test Outcomes:** The data shows that **[Insert %]** of all tests return "Normal" results. However, a critical **[Insert %]** are "Abnormal," highlighting the severity of the patient mix.
* **Operational Efficiency:** A significant percentage of tests (**[Insert %]**) remains "Pending." This bottleneck is highest in the **[Insert Month]**, directly impacting discharge times.
* **Highest Abnormal Rates:** The condition **[Insert Condition Name]** consistently shows the highest rate of abnormal test results.

### 🏥 **3. Hospital & Doctor Performance**
* **Workload Analysis:** **Dr. [Insert Name]** handles the highest caseload. Simultaneously, **[Insert Hospital Name]** receives the largest inflow of patients.
* **Performance Metrics:** Analyzing "Abnormal Rates" per doctor helps distinguish between routine checkups and complex case management.

### 💰 **4. Financial Performance & Cost Trends**
* **Billing Analysis:** The total revenue is **$[Insert Total]**, with an average cost per patient of **$[Insert Avg]**.
* **Cost Drivers:** Emergency admissions prove to be significantly more expensive on average compared to elective ones.
* **Insurance Insights:** **[Insert Provider Name]** covers the highest billing amounts per claim, making it the most valuable financial partner.

### ⏳ **5. Time-Based Operational Trends**
* **Peak Periods:** Patient inflow spikes significantly during **[Insert Month]**, suggesting a seasonal pattern.
* **Length of Stay:** The average length of stay is **[Insert Days]** days. Conditions such as **[Insert Condition]** require hospitalization well above the average.

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
1.  **Resource Allocation:** Increase nursing staff and lab technicians during **[Peak Month]** to handle surges and reduce the "Pending Test" rate.
2.  **Financial Strategy:** Review the billing structure for **[Lowest Revenue Condition]** as it consumes resources with minimal financial return.
3.  **Operational Improvement:** Investigate the discharge process for **[Condition with High LOS]** to improve bed availability.

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
