# Order Automation for Clothing Store — n8n Workflow

## Problem

Small clothing businesses process orders manually:
- Customer fills out a form
- Owner copies data into a spreadsheet
- Owner manually sends confirmation email

This is slow, error-prone, and doesn't scale.

## Solution

End-to-end automation using n8n:


1. Customer fills out an order form
2. Data is automatically appended to a Google Sheet
3. Business owner receives an instant email notification

## Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation |
| Google Sheets API | Data storage |
| Gmail | Email notification |

## Screenshots

### Workflow Topology
![Workflow Topology](screenshots/02-workflow-topology.png)

### Order Form
![Order Form](screenshots/04-order-form.png)

### Google Sheet Output
![Google Sheet Output](screenshots/07-google-sheet.png)

### Email Notification
![Email Subject](screenshots/05-email-subject.png)
![Email Body](screenshots/06-email-body.png)

## Skills Demonstrated

- Event-driven automation
- API integration
- Data pipeline design
- No-code/low-code workflow building

## Cybersecurity Relevance

This workflow mirrors what happens in a SOC:

| This Project | SOC Equivalent |
|--------------|----------------|
| Form submission | SIEM alert |
| Append to Google Sheet | Log to database |
| Send email | Notify analyst |
| n8n workflow | SOAR playbook |

## How to Use

1. Download `workflow.json`
2. Import into n8n
3. Configure credentials (Google Sheets, Gmail)
4. Activate the workflow

## Connect

- **LinkedIn:** [linkedin.com/in/adel-boutaghane](https://www.linkedin.com/in/adel-boutaghane-54b982386)
- **GitHub:** [github.com/agurzil-kutama](https://github.com/agurzil-kutama)
