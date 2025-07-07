# 📊 Loan Risk Analytics – Python + Tableau

## 🎯 Project Objective
To analyze LendingClub's loan data to identify patterns of default, segment borrowers by risk, and uncover insights that can improve credit decision-making.

---

## 🔍 Key Questions Answered
- Which loan terms, grades, and purposes are riskier?
- How do FICO scores and DTI ratios relate to default likelihood?
- Can we segment borrowers into Low / Medium / High risk using FICO and DTI?

---

## 🧰 Tools & Techniques
- **Python**: Pandas, NumPy, Seaborn, Matplotlib
- **Data Cleaning**: Handled nulls, dropped unused columns, created `fico_avg`, `default_flag`, `risk_band`
- **EDA**: Visualized term distribution, default by grade & purpose, FICO boxplot vs default
- **Tableau**: Interactive dashboard with KPI tiles, filterable charts, and risk insights

---

## 📁 Files Included
- `loan_risk_analysis.ipynb` – Full EDA and preprocessing notebook
- `loan_risk_analysis_final.csv` – Cleaned dataset for Tableau
- `dashboard.png` – Snapshot of Tableau dashboard

---

## 📸 Tableau Dashboard Preview
> <img width="791" alt="Tableau Dashboard" src="https://github.com/user-attachments/assets/f94890ec-bc0b-4d70-87d2-f7ab28b36cf9" />


---

## 🌐 Tableau Public Link
> https://public.tableau.com/app/profile/vaishali.jain7381/viz/LoanRiskAnalytics/Dashboard1

---

## 📈 Key Insights
- 60-month loans and lower-grade loans (E, F, G) show higher default rates
- Default rate increases significantly when DTI is high and FICO is low
- Small business and renewable energy loans are riskiest in terms of purpose
- Risk segmentation (Low, Medium, High) aligns well with observed default trends

---

## 👩‍💻 Author
**Vaishali Jain**  
Aspiring Data Analyst | Python • SQL • Tableau | Domain: Financial Analytics

---

