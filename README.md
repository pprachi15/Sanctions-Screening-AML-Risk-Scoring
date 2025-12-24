# Sanctions Screening and AML Risk Scoring (SQL Project)

This project simulates a real-world **Sanctions Screening and Anti–Money Laundering (AML) Risk Scoring Engine**, similar to the workflows fintech compliance teams use to detect high-risk users, reduce false positives, and prioritize operational workload.

---

## 📌 Project Overview

The SQL workflow performs **five key AML functions**:

### 1. Sanctions Match Detection  
A similarity score identifies potential matches with sanctions or OFAC lists.

### 2. Multi-Factor AML Risk Scoring  
Each user receives a risk score based on:
- Strength of name match
- Country risk level (High, Medium, Low)
- Transaction pattern risk
- Repeat-offender behavior

### 3. False Positive Filtering  
Alerts triggered by strong name similarity but **low-risk geography** are flagged as potential false positives, reducing noise for compliance analysts.

### 4. Risk Tier Classification  
Based on total risk score, users are categorized into:
- **High Risk**
- **Medium Risk**
- **Low Risk**

This mirrors how real AML teams triage alerts.

### 5. Compliance Workload Summary  
A snapshot of:
- Total sanctions-triggered alerts
- Alerts from name matches
- Alerts from high-risk geographies
- Pending/unresolved cases

This helps identify where compliance teams may face bottlenecks.

---

## 📊 Key Insights

- A few users combine **high name-match score + high-risk country + suspicious transaction behavior**, making them likely true positives requiring deeper investigation.
- Several alerts score lower than expected, indicating **potential false positives** — a major cost-driver in AML operations.
- Pending decisions still form a large part of the workload, showing how **operational backlog** can slow down regulatory processes.
- Risk-tiering helps align automation and manual reviews so analysts spend time on the most meaningful alerts.

---

## 🧠 Why This Project Matters

Sanctions and AML systems are foundational to any financial institution.  
This project demonstrates how structured SQL logic can:

✔ Reduce unnecessary manual review  
✔ Improve sanctions accuracy  
✔ Minimize regulatory exposure  
✔ Prioritize high-risk users  
✔ Strengthen overall compliance posture  

Real fintech companies like Stripe, Revolut, Cash App, Goldman Sachs, and JPMorgan maintain similar rule engines as part of their internal monitoring.

---

## 🛠 Skills Demonstrated

- SQL-based risk scoring
- Compliance modeling and logic design
- Boolean classification and tiering
- Anti–money laundering fundamentals
- Data storytelling for risk and operations
- Understanding of regulatory workflows inside fintech

---
## 🙋‍♀️ Author Note

P.S.: I am a strategic problem solver with experience in analytics and program management, currently with **12 days left on F1 OPT**, and working intentionally toward my next opportunity.  
If my work aligns with the needs of your team, I would welcome a conversation. ✨

