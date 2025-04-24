# Banking Risk Analytics Dashboard (2025)  
**Power BI | MySQL | Python**  
*Inspired by [Satyajit Pattnaik's Power BI Tutorial](https://www.youtube.com/watch?v=qlYT2VIyaaY)*  

---

## 📊 **Dashboard Overview**  
Analyzing **$2.19B in loans** and **$1.87B in deposits** across 1,488 clients with:  
✔ **Risk Metrics**: 3.9% NPA, default probability models  
✔ **Customer Segments**: Gender, income bands (High/Med/Low), occupation  
✔ **Financial KPIs**: $215.11M revenue, 180% customer growth  

[![Dashboard Preview]](https://app.powerbi.com/view?r=eyJrIjoiNjI5YWExMmQtODIyNS00MTE0LWE2ZTYtNWZmOWNhOWY1OTc5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) 

---

## 🖥️ **Dashboard Sections**  

### 1. **Home View**  
- **Key Metrics**:  
  ```plaintext
  TOTAL LOANS       $2.19B
  TOTAL DEPOSITS    $1.87B 
    ↳ Checking: $474.91M
    ↳ Savings:  $353.04M
  BUSINESS LENDING  $1.29B

  - **Filters**: `Joining Year (2008-2021)` | `Gender` | `Income Band`  

### 2. Loan Analysis  
#### Key Visualizations:
- **Loans by Nationality**  
 **Top Occupations by Loan Value**  

  | Occupation           | Loan Amount |
  |----------------------|-------------|
  | VP Marketing         | $3.4M       |
  | Accountant II        | $2.1M       |
  | Software Consultant  | $1.8M       |

### 3. Deposit Analysis  
#### Key Insights:
- **Deposit Distribution**  
```mermaid
pie
  title Deposit Types
  "Commercial" : 56.5
  "Institutional" : 26.12
  "Private Bank" : 17.38

