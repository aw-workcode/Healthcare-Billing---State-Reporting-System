# Healthcare State Reporting & Billing Compliance System

## 📌 Overview  
This project automates **healthcare state reporting workflows** for mental health and substance use treatment providers, mirroring tasks like Florida Medicaid billing compliance. It includes:  
- Synthetic patient data generation  
- **State-compliant CSV report generation** (e.g., invoiced amounts by service date)  
- Revenue journal entry automation  
- Data quality checks and validation  
- Trend analysis for service forecasting  

Built for accuracy and scalability, it reflects real-world tasks from the [Meridian Data Analyst - State Reporting job description](#).  

---

## 🔑 Key Compliance Features  
✅ **State File Formatting**  
   - ISO-standard dates (`YYYY-MM-DD`)  
   - Financial precision (2 decimal places)  
   - Column headers optimized for state systems  

✅ **Data Validation**  
   - Missing value detection/removal  
   - Type checking (dates, numeric fields)  

✅ **Financial Reporting**  
   - Daily invoiced amount aggregation  
   - Insurance adjustment reconciliation  
   - Net revenue calculations for journals  

✅ **SQL Integration**  
   - Querying for service-type trends  
   - Database schema design (SQLite)  

---

## 🛠️ Technologies Used  
- **Python**: `pandas` (data cleaning/aggregation), `numpy` (financial calculations), `faker` (synthetic PHI-safe data)  
- **SQL**: Query optimization, data validation  
- **Data Visualization**: `matplotlib/seaborn` (billing trend analysis)  
- **Tools**: Jupyter Notebook (prototyping), SQLite (database management)  

---

## 📂 Project Relevance to the Role  
This project directly addresses requirements from the **Meridian Data Analyst - State Reporting** job description:  

| **Job Requirement**               | **Project Implementation**                                                                 |  
|-----------------------------------|-------------------------------------------------------------------------------------------|  
| Build/transmit state files        | Generated state-compliant `state_reporting.csv` with validated dates and financial data   |  
| Create journal entries            | Automated `journal_entries
