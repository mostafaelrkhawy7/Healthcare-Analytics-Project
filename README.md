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

### 🔹 2. Key Measures (KPIs) & Performance
The following metrics were calculated to measure hospital performance:

#### 🩺 Medical KPIs (Accuracy & Load)
| Measure | Value | Insight |
|:---|:---|:---|
| **Normal Test Rate** | **25.07%** | Represents healthy outcomes. |
| **Abnormal Test Rate** | **50.07%** | **Critical:** Half of all patients show clinical issues. |
| **Pending Test Rate** | **24.85%** | **Bottleneck:** 1 in 4 tests are stuck in the lab queue. |

#### 💵 Financial & Operational KPIs
| Measure | Value | Insight |
|:---|:---|:---|
| **Total Billings** | **$1.41 Billion** | Massive revenue stream driven by chronic cases. |
| **Average Billing** | **$25,539** | High avg cost indicates complex treatments. |
| **Total Patients** | **40,235** | Total unique patient volume analyzed. |
| **Avg Length of Stay** | **15.6 Days** | Driven largely by Asthma & Chronic cases. |

---

## 📈 Deep Dive Insights (Data Storytelling)

### 🌍 **1. Patient Demographics & Trends**
* **Youth Dominance:** The **19–35 age group** represents the highest share of hospital visits (**37%**), indicating a young, active population with increasing medical needs.
* **Complexity in Mid-Life:** The **36–60 segment (36%)** presents more complex conditions, suggesting a higher hospitalization risk as age increases. Children (0–18) represent the smallest share.
* **🚀 Key Insight:** The critical age segment for resource planning is **36–60**, as they show both high patient volume and high-severity conditions.

### 🔬 **2. Medical Conditions & Severity**
* **Chronic Dominance:** **Hypertension, Arthritis, and Cancer** are the top 3 medical conditions, indicating that chronic diseases drive the majority of patient admissions.
* **Stay Duration:** **Asthma** shows the longest average stay (~15.7 days), which is not aligned with its patient frequency, suggesting high complication severity per case rather than just volume.
* **🚀 Key Insight:** **Asthma & Diabetes** have lower overall volume but a **higher impact per patient**, which should guide specific resource optimization.

### 🧪 **3. Diagnostic Efficiency & Lab Bottlenecks**
* **High Acuity:** The **50.07% abnormal result rate** is extremely high, indicating the hospital treats more acute and serious cases rather than routine check-ups.
* **Operational Drag:** The **25% pending rate** highlights a critical operational bottleneck, likely caused by understaffed labs or peak month congestion (Jan–Mar & Aug).
* **🚀 Key Insight:** Pending results directly correlate with a **higher Length of Stay**, negatively impacting bed turnover and overall hospital efficiency.

### 🏥 **4. Hospital & Doctor Performance**
* **Operational Hub:** **LLC Smith** receives the highest number of patients, positioning it as the network's operational center.
* **Top Performer:** **Dr. Michael Smith** leads in both billing and patient count, demonstrating high patient trust or specialization in complex cases.
* **Resource Needs:** Hospitals with high abnormal test counts (e.g., **Smith Group**) are treating more complicated cases.
* **🚀 Key Insight:** Facilities with high abnormal test ratios should be **prioritized for advanced medical equipment investment**.

### 💰 **5. Financial Performance**
* **Revenue Drivers:** Total Billings of **$1.41B** are dominated by **Diabetes, Obesity, and Arthritis**.
* **Cost Analysis:** **Emergency cases** are the most expensive admission type, suggesting resource-heavy treatments and higher medication usage.
* **🚀 Key Insight:** The combination of **High-cost Emergency cases** + **Long-stay Asthma cases** are the major drivers of budget consumption.

### ⏳ **6. Time-Based Patterns**
* **Seasonal Peaks:** **January & August** stand out as peak months. January likely reflects post-holiday stress/chronic flare-ups, while August may relate to heat-related complications (Asthma/Hypertension).
* **🚀 Key Insight:** **YoY growth** shows a steady increase in admissions, indicating that hospital demand is expanding faster than current operational capacity.

---

## 📊 Strategic Results & Recommendations

### 💡 1. Operational Efficiency
* **Action:** Prioritize reducing the **Pending Test Rate (24.85%)**.
* **Strategy:** Add lab technicians during peak months (Jan/Aug) and introduce automated test processing systems to clear the backlog.

### 💡 2. Financial Optimization
* **Action:** Review **Emergency case costs** for potential over-utilization of resources.
* **Strategy:** Consider introducing **fixed-price packages** for chronic conditions like Hypertension and Diabetes to stabilize revenue predictability.

### 💡 3. Medical Programs
* **Action:** Launch a **Chronic Disease Care Program**.
* **Strategy:** Focused care for Arthritis and Diabetes can reduce the Average Length of Stay and improve patient outcomes. Introduce rapid-response treatment pathways specifically for **Asthma**.

### 💡 4. Insurance Management
* **Action:** Leverage the partnership with **Cigna** (Top Contributor).
* **Strategy:** Renew the partnership with optimized terms and encourage patients to shift to high-performing insurance providers to improve cash flow.

### 💡 5. Capacity Planning
* **Action:** Address the long stay duration for **Asthma**.
* **Strategy:** Allocate more respiratory specialists and dedicate specific monitoring units to Asthma patients to reduce their 15+ day average stay.

---

## 📎 Files Included
- `Healthcare.xlsm` — Complete Excel file with raw data, Power Query steps, Data Model, and final Dashboards.

---

## 🚀 How to Use
1. Open `Healthcare.xlsm` in Microsoft Excel.
2. Enable Macros/Content if prompted (for interactivity).
3. Navigate to the **Dashboard** tabs.
4. Use **Slicers** (Year, Condition, Hospital, Test Status) to filter the data dynamically.

---

## 👨‍💻 Author
**Mostafa Elrkhawy** Excel & BI Analyst  
📧 [LinkedIn Profile](https://www.linkedin.com/in/mostafa-elrkhawy/)  
📅 **Project Type:** Healthcare Data Analytics & Dashboarding
