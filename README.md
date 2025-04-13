# 💸 Fintech Loan Risk Analysis – Power BI Dashboard

This project explores the relationship between applicant characteristics and loan performance in a fintech lending dataset. Built using Power BI, the dashboard reveals patterns in loan approvals, default risk, and customer profiles—providing actionable insights to enhance credit risk management.

---

## 📌 Problem Statement

> Identify the factors that most influence loan approval decisions, providing insights to optimize the approval process and reduce the risk of defaults.  
> Determine parameters that relate to potential default behavior, enabling better decision-making while processing loan applications.

---

## 🔍 Business Questions Addressed

- **What percentage of defaulters exist in the application data?**
- **How many applicants are married and what percentage do they represent?**
- **What is the most frequently occurring family size among applicants?**
- **Which is the most common occupation type among applicants?**
- **What percentage of applicants are male?**
- **How much of the total loans are revolving credit types (e.g., credit cards)?**
- **Is there a correlation between work experience and total income?**
- **What is the total amount of loan approved recently?**
- **How many additional documents (excluding the application form) are submitted in most applications?**
- **What is the correlation between total house area and average credit amount?**
- **What is the relationship between average credit requested and total income?**
- **How many applicants bought a new phone in the last month?**
- **How many current applicants have at least one previously approved loan?**
- **What is the second-highest product category for which previous loans were approved, and how many?**
- **How many of the active previously approved loans are at risk of default, considering the current default status?**
- **Do loans approved at the end of the day have more defaults?**
- **Do loans approved at the end of the week show higher default rates?**
- **How many applicants already have credit cards issued by the same bank?**
- **How many have taken some form of loan previously (credit bureau)?**
- **How many applicants have applied for loans previously in the same bank?**
- **How many current applicants made lesser payments for installments on previous loans?**
- **What percentage of those with lesser previous payments also defaulted on the recently approved loan?**
- **What is the maximum number of previously approved loans per applicant?**
- **How many applicants defaulted even after successfully completing a previous loan?**
- **Have applicants who drew cash from credit cards defaulted?**
- **How many users have 5 active previously approved loans?**
- **How many defaulters have more than 3 loans among previously approved loans?**

---

## 📈 Key Insights

- Most defaulters had **prior missed installment payments**.
- Majority of **defaulters withdrew cash** from credit cards.
- **Family size = 2** is most common, and **laborers** dominate occupation type.
- Male applicants form ~65% of total applicants.
- Over **90% of loans are cash loans**, with less than 10% being revolving credit.
- **Experience and total income** show a mild positive correlation.
- Loans approved in the **middle of the week and work hours** tend to have higher default risks.
- **Applicants with ≥5 loans** or multiple approvals show a pattern of higher risk.

---

## 📊 Dashboard Features

- KPI metrics: Total loan amount, # of risky loans, loan behavior over time.
- Correlation visualizations: Income vs Credit, House Area vs Credit, Experience vs Income.
- Demographics: Gender, Family Size, Marital Status, Occupation.
- Defaults by time (day/hour), prior loan status, and payment behavior.
- Interactive filters and tooltips for deep drilldowns.

---

## 💡 Recommendations

1. Prioritize applicants with **clean repayment histories** over those with multiple loan applications or defaults.
2. Flag risky profiles based on:
   - Missed installment payments
   - Cash withdrawals via credit cards
   - >3 previously approved loans
3. Introduce **stricter checks during mid-week approval periods** and **working hours**.
4. Use document submission behavior as a **reliability indicator**.
5. Incorporate **product categories and phone purchase behavior** as behavioral predictors.
6. **Segment applicants** based on experience, family size, and income for tiered risk scoring.
---   
## 🛠️ Tools & Technologies Used
Power BI – For building interactive dashboards and data visualization.

Power Query – For data cleaning, transformation, and merging.

DAX (Data Analysis Expressions) – For calculated measures and custom columns.

CSV files – Used as the primary data source.

Power BI Relationships – To establish connections between multiple data tables.

---
## 🙋‍♂️ Author
Lakshmi Bhargavi Duvvuri


