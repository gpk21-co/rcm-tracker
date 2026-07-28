# ⚡ Candid Health — Touchless RCM & AI Resolution Tracker

An interactive product prototype and analytics dashboard demonstrating automated Revenue Cycle Management (RCM) KPI monitoring and AI-driven claims resolution workflows.

---

## 📌 Context & Problem Statement
Healthcare providers face significant revenue leakage due to uncollected claims, missing documentation, and billing errors. Industry standards recommend maintaining a **Net Collection Rate (NCR) between 95–99%** and keeping **Days in Accounts Receivable (A/R) under 50 days**. 

Using a synthetic dataset of 1,000 healthcare claims (`claim_data.csv`), this project identifies key financial bottlenecks and models how Candid Health's automated platform and AI agents can restore revenue collection to benchmark levels.

---

## 📊 Quantitative Analysis Key Findings
* **Baseline Net Collection Rate (NCR):** **89.98%** (Total Paid: **$200,754** / Total Allowed: **$223,112**), lagging behind the 96% industry benchmark.
* **Recoverable Revenue Opportunity:** Reaching target NCR yields **+$13,433.52** in recovered revenue.
* **Days in A/R Aging:** Averages **82.0 days** (Benchmark: **<50 days**), with **72.8%** of claims exceeding 50 days.
* **Top Friction Points:** Authorization Issues (154 claims), Incorrect Billing Info (142 claims), and Patient Eligibility (126 claims).

---

## 🚀 Key Prototype Features
1. **Executive Benchmark Monitor:** Real-time visibility into NCR, A/R timeline, and target revenue recovery metrics.
2. **Predictive Root-Cause Analytics:** Breakdown of claim issues across insurance types and denial reason codes.
3. **AI Touchless Action Queue:** Interactive workflow delegating flagged claims to automated AI agents (*AuthAgent-v2*, *CleanClaim-AI*, *EligiBot-v1*).

---

## 🛠️ Tech Stack & Setup
* **Language:** Python
* **Libraries:** Streamlit, Pandas, Plotly
