
## 🏥 **CMS Nursing Home COVID-19 Dashboard (Excel Project)**

*Transforming federal nursing home data into clear, actionable insights on COVID-19 trends, vaccination coverage, and reporting quality.*

---

### 📘 **Project Overview**

The COVID-19 pandemic placed **U.S. nursing homes** at the center of one of healthcare’s toughest challenges — protecting high-risk residents while ensuring accurate, transparent reporting.

In this project, I analyzed the **CMS Nursing Home COVID-19 dataset**, which originally contained **14,791 records** from facilities across all **50 states**. Using **Excel (Power Query + DAX Measures)**, I cleaned and explored the dataset to uncover how well facilities reported infection rates, vaccination progress, and data quality.

---

### ⚙️ **Tools & Techniques**

| Tool / Feature            | Purpose                                              |
| ------------------------- | ---------------------------------------------------- |
| **Microsoft Excel**       | Main analysis & dashboarding environment             |
| **Power Query**           | Data cleaning & transformation                       |
| **DAX Measures tab**      | Custom calculations for vaccination % and QA metrics |
| **PivotTables & Slicers** | Interactivity and comparative insights               |
| **Dashboard Pages**       | Organized into *State, Facility, and QA* views       |

---

### 🎯 **Project Objectives**

* Identify the states and facilities most affected by COVID-19
* Compare vaccination coverage between residents and staff
* Evaluate the accuracy and completeness of reported data
* Design a **three-page Excel dashboard** to explore results interactively

---

### 🧹 **Data Cleaning & Preparation**

The raw dataset contained several inconsistencies, including blank provider numbers, invalid IDs, and missing vaccination entries.
Cleaning was performed entirely in **Power Query**:

* Removed irrelevant or duplicate columns
* Filtered out **253 rows** with blank or invalid provider numbers
* Replaced categorical shorthand (e.g., “Y” → “Yes”) for readability
* Recalculated vaccination metrics using **DAX Measures**
* Reduced dataset from **14,791 → 9,167 rows**, ensuring accuracy and reliability

---

### 📊 **Dashboard Pages Overview**

The final Excel dashboard was designed around **three analytical perspectives**:

| Dashboard Page                  | Focus                           | Description                                                             |
| ------------------------------- | ------------------------------- | ----------------------------------------------------------------------- |
| **State Dashboard**             | Geographic & Vaccination Trends | Compare infection rates, deaths, and vaccination coverage across states |
| **Facility Dashboard**          | Facility Performance            | Identify top facilities and data submission consistency                 |
| **Quality Assurance Dashboard** | Data Integrity                  | Assess reporting completeness, QA pass rates, and submission gaps       |

---

## 🌍 **State-Level Insights**

> “State patterns reveal where reporting quality and vaccination efforts made the biggest difference.”

**GENERAL INSIGHTS:**
After cleaning, **9,167 valid rows** remained and were analyzed for state-level performance.

### 🔎 **Observations:**

1. **5,385 COVID-19 cases** and **0 deaths** were recorded — this could signal either **faulty reporting** or **vaccine effectiveness** in preventing severe outcomes.
2. **39% of residents** and **7% of staff** were vaccinated — revealing a **critical immunization gap** among healthcare workers.
3. **Ohio** reported the **highest number of confirmed cases**, while **Vermont** led in **resident vaccinations**, and **Hawaii** had the **highest staff vaccination rates**.

### 💡 **Recommendations:**

1. Reinforce **accurate data entry** — avoid leaving blank columns to reduce null values.
2. Implement **staff vaccination campaigns** to close the immunization gap and reduce infection risk.

---

## 🏥 **Facility-Level Insights**

> “Strong data quality reveals best-performing facilities — but data exclusions may hide system-wide weaknesses.”

**GENERAL INSIGHTS:**
This analysis focused only on facilities that passed QA checks and submitted complete records, representing **top-performing institutions**.

### 🔎 **Observations:**

1. Most facilities reported **fewer than 50 confirmed cases**, suggesting effective management of COVID-19 outbreaks.
2. **High data exclusion rates** post-cleaning indicate potential **reporting bias**, as facilities with incomplete submissions were removed.

### 💡 **Recommendations:**

1. Encourage **proper data entry practices** to prevent data loss and bias in analysis.
2. Use high-performing facilities as **benchmarks** for infection control and data management.

---

## ✅ **Quality Assurance Insights**

> “Data quality determines the credibility of public health reporting — accuracy is as important as infection control.”

**GENERAL INSIGHTS:**
Using the **uncleaned dataset (minus irrelevant columns)**, a quality analysis was conducted to evaluate overall reporting integrity.

### 🔎 **Observations:**

1. **66%** of the raw data passed the **Quality Assurance (QA)** check.
2. Only **62%** of the data was retained after cleaning.
3. Nearly **40% of facilities** were excluded — possibly introducing **bias** for under-represented states or low-reporting facilities.

### 💡 **Recommendations:**

1. Conduct **training sessions** for staff at facilities with poor data submission rates.
2. Implement **automated feedback loops** or **data entry alerts** to flag incomplete submissions in real time.
3. Require **regular QA performance reporting** by state and facility to maintain accountability.

---

### 🧭 **Key Takeaway**

This project demonstrates how **Excel**, combined with **Power Query** and **DAX measures**, can move a complex federal dataset from **raw, error-prone entries** to **meaningful insights** about healthcare performance and data reliability.

> Beyond tracking COVID-19 cases, this analysis highlights the urgent need for **standardized digital reporting** to strengthen public health responses in future crises.

---

### 🗂️ **Repository Guide**

| Section                    | Description                              |
| -------------------------- | ---------------------------------------- |
| `📄 Project_Summary.pdf`   | One-page summary of insights and visuals |
| `📊 Dashboard_Screenshots` | Key visuals from each dashboard page     |
| `🧮 Cleaned_Data.xlsx`     | Processed dataset after transformation   |
| `README.md`                | Full project explanation and methodology |

---

### 🧠 **Reflection**

Working on this dataset sharpened my ability to:

* Perform **data quality assessment** in Excel
* Derive **insightful trends** from messy, real-world healthcare data
* Translate results into **operational and policy recommendations**

