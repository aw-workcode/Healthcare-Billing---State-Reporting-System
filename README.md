# Healthcare State Reporting & Billing Compliance System

## 📌 Overview  
This project automates **healthcare state reporting workflows** for mental health and substance use treatment providers, mirroring tasks like Florida Medicaid billing compliance. It includes:  
- Synthetic patient data generation  
- **State-compliant CSV report generation** (e.g., invoiced amounts by service date)  
- Revenue journal entry automation  
- Data quality checks and validation  
- Trend analysis for service forecasting  

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
