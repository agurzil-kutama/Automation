# Automation
Automation workflows and scripts — n8n, Python, Bash, and more. Building event-driven systems for business and security operations.
# Automation Projects

A collection of automation workflows and scripts — built with n8n, Python, Bash, and more .

This repository documents my journey into event-driven automation, from simple business workflows to security-focused SOAR playbooks.

---

## Repository Structure
automation/
├── n8n/ # n8n workflow automations
│ ├── order-automation/ # Order processing workflow
│ └── README.md # n8n folder guide
├── python-scripts/ # Python automation scripts
│ └── README.md
├── bash-scripts/ # Bash automation scripts
│ └── README.md
└── README.md


---

## Projects

### 🔄 Order Automation (n8n)

**Problem:** Small businesses manually process orders — copying data, sending emails, updating spreadsheets.

**Solution:** End-to-end automation:
1. Customer fills out an order form
2. Data is appended to Google Sheets
3. Business owner receives an email notification

**Tech Stack:** n8n, Google Sheets API, Gmail

**Skills Demonstrated:** Event-driven automation, API integration, data pipeline design

**Status:** ✅ Complete

**📂[View the project](./projects/n8n/1-order-automation-for-clothing-store/)**

---

## Why This Matters for Cybersecurity

This workflow follows the same logic as SOAR playbooks and SIEM automation:

- **Input** → Alert / form submission
- **Process** → Parsing, enrichment, formatting
- **Action** → Store data / send notification / trigger response

Understanding event-driven automation is a core skill for SOC analysts, security engineers, and anyone working with SIEM, SOAR, or incident response.

---

## Upcoming Projects

- **Security Alert Enrichment** — VirusTotal + AbuseIPDB integration
- **Log Parser** — Python script for parsing security logs
- **Backup Automation** — Bash script for scheduled backups

---

## Connect

- **LinkedIn:** [linkedin.com/in/adel-boutaghane](https://www.linkedin.com/in/adel-boutaghane-54b982386)
- **GitHub:** [github.com/agurzil-kutama](https://github.com/agurzil-kutama)

