# Secure Digital Asset Operations (SDAO) Monitoring Dashboard

## 📌 Project Overview
This project simulates an institutional crypto-custody monitoring environment. It focuses on **Key Hygiene**, **Policy Compliance**, and **Operational Triage** for HSM (Hardware Security Modules) and MPC (Multi-Party Computation) nodes.

## 🛠️ The Challenge: Data Integrity & Drift
In real-world custody operations, logs from disparate sources often contain epoch errors or missing timestamps. I identified and resolved a **126-year date offset error** (system baseline 1899) using Power Query transformations to ensure accurate reporting for the 2026 operational cycle.

## 📊 Key Features
- **90-Day Rotation Baseline:** Automated tracking of key "staleness."
- **Institutional Triage:** Conditional formatting that highlights high-risk assets (Key Age > 90 days) in **Red**.
- **Fleet Health Gauge:** A high-level KPI showing average fleet hygiene against security targets.
- **Multisig Analysis:** Monitoring signer weights and successful vs. failed signing events.

## 🚀 Tech Stack
- **Power BI:** Data Visualization & DAX (Data Analysis Expressions)
- **Power Query (M):** ETL & Schema Normalization
- **Python:** Synthetic Data Generation for Edge-Case Testing
