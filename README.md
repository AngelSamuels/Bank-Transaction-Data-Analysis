📊 Bank Transactions Analysis — October 2025
A complete end‑to‑end analysis of transactional behavior, fraud patterns, failure rates, and latency performance using Excel, SQL, and Power BI. 
This project demonstrates the full analytics workflow: data cleaning, exploratory analysis, dashboard design, and insight generation.

🎯 Objective
To analyze a month of banking transaction data (October 2025) and uncover patterns related to:
- Fraud behavior
- Transaction failures
- Latency performance
- Device and transaction‑type differences
- Systemic vs isolated operational issues
The goal is to identify actionable insights that could support fraud prevention, operational monitoring, and backend system optimization.

🛠️ Tools Used
- Excel — data cleaning, preprocessing, and static dashboard
- SQL — fraud, failure, and latency analysis queries
- Power BI — interactive dashboard and visual exploration

🔍 Key Findings
🕵️ Fraud Analysis
- Fraud rates across Deposit, Withdrawal, and Transfer remain consistently high (~45–50%).
- No single transaction type dominates → fraud is systemic, not isolated.
- Mobile devices show slightly higher fraud rates than Desktop.
- Fraud spikes at specific minutes suggest coordinated or bursty attempts
❌ Failure Analysis
- Mobile and Desktop have nearly identical failure rates (~50%).
- Failures are not device‑specific → likely tied to backend or shared processing layers.
- Withdrawal, Deposit, and Transfer show similar failure rates, reinforcing system‑level issues.
⏱️ Latency Analysis
- Average latency remains stable at 11–12 ms, well within acceptable performance.
- Some transactions fail even at low latency → failures are not performance‑driven.
- Latency by minute shows minimal variation, confirming network stability

🧠 Conclusions
Across fraud, failure, and latency metrics, the patterns point to systemic backend issues rather than device‑specific, transaction‑specific, or performance‑related problems.
Consistent behavior across categories suggests that the root cause sits within shared processing logic, validation rules, or infrastructure layers — not at the edges of the system.
This analysis highlights the importance of cross‑functional investigation when multiple metrics move together in predictable ways.


