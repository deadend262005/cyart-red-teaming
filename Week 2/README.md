# Week 2 – Practical Application

This folder contains documentation, screenshots, rules, and workflow for Week 2 tasks.

## Structure
- `Week2_Practical_Application_Report_Final.docx` – Final consolidated report
- `screenshots/` – Images and figures used in the report
- `rules/` – Sigma and Suricata rules
- `tables/` – CSVs for hunting results and capstone alerts

## Quick Links
- Sigma Rule: `rules/sigma_powershell.yml`
- Suricata Rule: `rules/suricata_malicious_ip.rules`
- Threat Hunting Table: `tables/threat_hunting_table.csv`
- Capstone Alerts: `tables/capstone_alerts.csv`

## How to Reproduce
1. Elastic Security: Query Event ID 4688 for PowerShell executions.
2. Sigma: Import `sigma_powershell.yml` (adjust to your pipeline).
3. Suricata: Load `suricata_malicious_ip.rules` and test by pinging from blocked IP.
4. IR: Use Velociraptor to collect `processes` and `netstat` artifacts.
5. Risk: Calculate ALE = 10,000 × 0.2 = 2,000.

_Last updated: 2025-08-24 18:37:53_
