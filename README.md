# CMS Nursing Home COVID-19 Dashboard  

### 📌 Project Description  
An exploratory analysis of the CMS COVID-19 Nursing Home dataset (14,791 rows across facilities in all 50 U.S. states) using **Excel**.  
The project identifies the most affected states and facilities, evaluates vaccination rates among residents and staff, and highlights data quality issues.  

---

### 📂 Dataset Source  
- CMS (Centers for Medicare & Medicaid Services) Nursing Home COVID-19 Data  
- [Link to Dataset](https://data.cms.gov/)  

---

### 🛠️ Tools Used  
- Microsoft Excel (Power Query, Power Pivot, Pivot Tables, DAX)  

---

### 🔑 Key Steps  
**Data Cleaning**  
- Removed irrelevant columns and standardized data types  
- Filtered out 253 invalid provider rows & null values (reduced dataset to 9,167 rows)  
- Replaced categorical values (`Y` → `Yes`)  
- Formatted date and numerical fields  

**Data Analysis**  
- Created calculated measures (% resident vaccination, % staff vaccination, etc.)  
- Modeled relationships between cleaned data tables for quality checks  
- Used PivotTables for state- and facility-level summaries  

**Data Visualization**  
- Designed a **3-page Excel dashboard**:  
  1. Staff Vaccination Trends  
  2. Resident Vaccination Trends  
  3. Data Quality Issues  

---

### 📊 Dashboard Preview  
![Dashboard Page 1](./CMS%20Dashboard%20page%201.PNG)  
![Dashboard Page 2](./CMS%20Dashboard%202.PNG)  
![Dashboard Page 3](./CMS%20Dashboard%203.PNG)  

---

### 📈 Insights & Results  
- States in the Northeast had the **highest case rates** among residents.  
- Facilities with **low staff vaccination** correlated with higher resident infections.  
- Significant **data quality gaps** were found (incomplete submissions, invalid IDs).  
- After cleaning, only ~62% of the dataset was reliable for analysis.  

---

### 🔗 Files  
- [Cleaned Dataset (Excel)](./Cleaned_CMS_Data.xlsx)  
- [Dashboard File (Excel)](./CMS_COVID_Dashboard.xlsx)  

---

### 🌐 Live / Downloadable Version  
- [Download Dashboard File](./CMS_COVID_Dashboard.xlsx)  
