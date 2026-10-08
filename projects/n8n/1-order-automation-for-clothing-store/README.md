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

#### Files

| File | Purpose |
|---|---|
| `workflow.json` | Sanitized n8n export. Import this to run the workflow. |
| `screenshots/` | Visual proof of the workflow in action. |

### How to Export a Workflow from n8n

1. Open the workflow in your n8n instance.
2. Click the **three-dot menu (⋯)** in the top-right of the workflow editor.
3. Select **Export JSON**.
4. The file downloads as `<workflow-name>.json`.

### How to Import a Workflow into n8n

1. Open your n8n instance.
2. Click the **three-dot menu (⋯)** next to your workflow list, or in the editor.
3. Select **Import** → **From File**.
4. Choose the `workflow.json` file.
5. The workflow opens in the editor. Credential warnings appear on the Gmail and Google Sheets nodes — this is expected.
6. Click each node with a warning and configure your own credentials.
7. Replace the placeholders (`YOUR-WEBHOOK-ID`, `YOUR-SHEET-ID`, `your-email@example.com`) with your own values.
8. Save and activate the workflow.

### Screenshots

**n8n Dashboard**

![n8n dashboard overview](screenshots/1.png)

**Export and Import Menu**

![Export JSON and Import options in n8n](screenshots/2.png)

**Workflow Topology**

![Workflow topology in n8n editor](screenshots/3.png)
## Connect

- **LinkedIn:** [linkedin.com/in/adel-boutaghane](https://www.linkedin.com/in/adel-boutaghane-54b982386)
- **GitHub:** [github.com/agurzil-kutama](https://github.com/agurzil-kutama)
